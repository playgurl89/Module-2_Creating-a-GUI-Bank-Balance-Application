# Module-2_Creating-a-GUI-Bank-Balance-Application
Create an application for bank balances
Simple Bank Balance GUI Application
Overview

This project is a Java Swing application that simulates basic banking transactions through a graphical user interface. The program allows a user to enter an initial account balance, deposit funds, withdraw funds, and view their updated balance throughout the session.

Rather than relying on console input and output, this application uses a GUI to create a more interactive user experience while demonstrating event-driven programming concepts covered in Java.

Project Purpose

The goal of this project was to gain hands-on experience working with Java Swing components and event handling. It demonstrates how graphical interfaces can be used to interact with users while performing common banking operations.

This application was developed as part of a programming assignment focused on:

GUI development using Java Swing
Event-driven programming
User input validation
Object-oriented programming concepts
Version control using Git and GitHub
Features

***Welcome screen requesting an initial account balance

***Real-time balance display

***Deposit functionality

***Withdrawal functionality with insufficient funds protection

***Input validation for invalid or empty entries

***Final balance display before exiting the application

***User-friendly graphical interface using Swing components

Technologies Used
Java
Java Swing
JPanel
JButton
ActionListener
Git
GitHub

How the Program Works
The user enters an initial account balance.
The application displays the current balance.
The user enters a transaction amount.
The user may:
Deposit funds
Withdraw funds
Exit the application
The balance updates automatically after each transaction.
Upon exiting, the program displays the final account balance.

Sample Test Cases

Test Case 1: Deposit Funds
Action	Value
Starting Balance	$500
Deposit	$100
Resulting Balance	$600

Test Case 2: Withdraw Funds
Action	Value
Starting Balance	$500
Withdraw	$50
Resulting Balance	$450

Test Case 3: Insufficient Funds
Action	Value
Starting Balance	$500
Withdraw	$1000
Result	Transaction Denied

Challenges and Lessons Learned

One of my favorite parts of this assignment was making my GUI unique and figuring out ways to make it a little different. While it's still pretty basic, I wanted it to be fun and interesting to interact with. One of the biggest challenges during development was designing the layout of the GUI. Initially, some components were not displaying correctly because multiple panels were assigned to the same region of the BorderLayout. Troubleshooting and correcting the layout helped reinforce how Swing containers and layouts work together.

This project also provided valuable experience handling user input, validating data, and responding to button events through ActionListeners.

Version Control

This project was maintained using Git and GitHub for version control. Multiple commits were used throughout development to track progress, test functionality, and document improvements.

Academic Reference

ZyBooks. (2025). CSC372 Programming II: Chapter 16 - Graphical User Interfaces. ZyBooks.

Available at: https://learn.zybooks.com/zybook/CSC372-1_20

Author

Samantha W.
Bachelor of Science in Computer Science
Colorado State University
