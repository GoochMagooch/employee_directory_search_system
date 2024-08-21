# employee_directory_search_system
You’ve been asked to build a simple employee directory search system for a company. The system needs to store employee names and their corresponding departments, and then allow a user to search for employees by department or by name. The company wants to use this to quickly find relevant contacts within different departments.

Challenge Requirements:
Data Structure:
Create a data structure (e.g., a dictionary or list of dictionaries) that stores employee names and their corresponding departments. You should initialize this data structure with at least 5 employees, each from different departments.

Add Employees:
Write a function add_employee(employee_name, department) that allows the addition of a new employee to the directory.

Search by Department:
Write a function find_by_department(department) that returns a list of all employees working in the given department.

Search by Name:
Write a function find_by_name(employee_name) that returns the department of the employee if found, or returns "Employee not found" if the employee does not exist in the directory.

Main Program:
Write a simple main program that:

Displays a menu with options to add an employee, search by department, search by name, or exit.
Repeats until the user chooses to exit.
Additional Parameters:
Input Validation: Ensure that the user’s input is valid, for example, that they provide non-empty strings for names and departments.
Edge Cases: Handle cases where the user searches for a department or employee that does not exist.
Clear Output: Ensure that the output is clear and formatted properly so that the user can easily read the results.

Example Usage:
Welcome to the Employee Directory Search System

1. Add an Employee
2. Search by Department
3. Search by Name
4. Exit

Please choose an option (1-4):
Option 1: User can add a new employee.
Option 2: User can search for employees by department and receive a list of all employees in that department.
Option 3: User can search for an employee by name and receive their department.
Option 4: Exits the program.

Expected Outcome:
This challenge will test your ability to work with dictionaries, write multiple functions, handle user input, and think about how a basic corporate system could be implemented in Python. It simulates a simplified employee directory system that is relevant to many corporate environments.