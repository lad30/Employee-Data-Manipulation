### Project Description:
This project consists of a series of exercises designed to practice data manipulation and functional programming techniques in Scheme. The tasks involve working with employee data represented as lists of tuples and include the following key functionalities:

1. Department Filtering: Recursively filter employees based on their department.
2. Name Extraction: Recursively extract the names of employees in a specific department.
3. Nested List Access: Retrieve elements from nested lists based on a list of indexes.
4. Salary Summation: Calculate the total salary of all employees using a tail-recursive approach.
5. Department Name-Salary Pairs: Use higher-order functions to list the names and salaries of employees in a specific department.
6. Average Salary Calculation: Compute the average salary of employees using foldl.
7. JSON Representation: Convert integers or lists of integers into their JSON string representation without whitespace.

## Requirements

To run this project, you will need the following:

1. Racket Installation:
Ensure that Racket is installed on your system. You can download it from racket-lang.org.

2. RackUnit Library:
This library is used for unit testing in Racket. It is included by default with Racket.

3. Racket Trace Library:
This is also included with Racket and is used for tracing function calls during debugging.

## Execution Steps

1. Install Racket:

Download and install Racket from https://racket-lang.org/
Follow the installation instructions specific to your operating system.

2. Setup Project File:

Create a new file named 'employee_data_manipulation.rkt'

3. Run the Program:

Open a terminal or command prompt.
Navigate to the directory containing 'employee_data_manipulation.rkt'
Run the file using the following command:
-> racket employee_data_manipulation.rkt

4. Testing the Functions:

The provided code includes unit tests using RackUnit. When you run the program, it will automatically execute these tests and display the results.
Check the output to ensure all tests pass. If any test fails, review the corresponding function for errors
