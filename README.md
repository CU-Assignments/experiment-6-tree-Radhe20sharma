22BCS15549    Radhe Sharma                                                                                                                     
                                                                                                                                                                          Java Stream Operations on Large Datasets

Overview

This project demonstrates the usage of Java Streams and Lambda Expressions to efficiently process a large dataset of products. The program performs the following operations:

Grouping Products by Category

Finding the Most Expensive Product in Each Category

Calculating the Average Price of All Products

Technologies Used

Java 8 or later

Java Streams API

Lambda Expressions

Collections Framework

Getting Started

Prerequisites

Ensure you have the following installed:

Java 8+ (Recommended: JDK 11 or later)

A Java IDE (Eclipse, IntelliJ IDEA, or VS Code) or a terminal with javac

Running the Program

Clone or download this repository.

Open the project in your preferred Java IDE or navigate to the folder in a terminal.

Compile the Java file:

javac ProductStreamProcessor.java

Run the program:

java ProductStreamProcessor

Code Explanation

The main file ProductStreamProcessor.java performs the following operations:

Creates a list of Product objects with name, category, and price.

Groups products by category using Collectors.groupingBy().

Finds the most expensive product per category using Collectors.maxBy().

Computes the average price using .mapToDouble().average().
