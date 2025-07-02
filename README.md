# pay-Rolll-Management-System
This project is a simple Employee Payroll System implemented in Java using Object-Oriented Programming (OOP) principles such as inheritance, abstraction, and polymorphism.

🚀 Features
Add and remove employees dynamically.
Support for:
Full-Time Employees (fixed monthly salary)
Part-Time Employees (hourly wage based on hours worked)
Display employee details along with their calculated salary.
Uses abstract classes and method overriding for flexible salary computation.

🧱 Class Structure
🔹 Employee (Abstract Class)
Fields: name, id

Abstract Method: calculateSalary()

Common functionality for all employees

🔹 FullTimeEmployee (Extends Employee)
Field: monthlySalary

Implements calculateSalary() as a fixed monthly amount.

🔹 PartTimeEmployee (Extends Employee)
Fields: hoursWorked, hourlyRate

Implements calculateSalary() as hoursWorked * hourlyRate

🔹 PayrollSystem
Maintains a list of employees

Provides methods to addEmployee, removeEmployee, and displayEmployees



