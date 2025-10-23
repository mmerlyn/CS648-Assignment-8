# CS648 - Assignment 8: Employee Management System

## Overview

This assignment implements a fully functional Employee Management System using JavaScript forms, DOM manipulation, and event handling. The application allows users to view, add, and delete employee records through an interactive web interface.

## The Employee Management System

Built a dynamic employee management application featuring:

- **Data Management**: Multi-dimensional array storing employee information (name, title, extension)
- **Initial Data**: Pre-populated with 5 employees for immediate viewing
- **Interactive UI**: Form-based interface for adding new employees
- **Dynamic Display**: Employee data rendered in a structured HTML table
- **Real-time Updates**: Table automatically refreshes when employees are added or deleted

## Key Features

### Employee Display

- Employees displayed in a clean, organized table format
- Four columns: Name, Title, Extension, and Delete Action
- Dynamic employee count in header (e.g., "Showing 5 Employees")
- Table updates automatically on add/delete operations

### Add Employee Functionality

- Three text input fields: Name, Title, Extension
- "Add" button to submit new employee data
- Form validation using JavaScript (not HTML5 attributes)
- Red error messages appear next to empty fields
- All fields required before submission

### Delete Employee Functionality

- Individual delete button for each employee row
- Removes employee from array and updates display
- Employee count automatically decrements

### Form Validation

- Custom JavaScript validation (no HTML5 `required` attribute)
- Checks all three input fields for values
- Displays error messages dynamically next to invalid fields
- Prevents submission if validation fails

## Technical Implementation

### Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- DOM API
- Event Listeners

### Key Concepts Demonstrated

- DOM manipulation and traversal
- Dynamic table generation
- Form handling and validation
- Event-driven programming
- Array operations (add, delete, iterate)
- Multi-dimensional arrays
- Input validation
- Error handling and user feedback

### DOM Scripting Techniques

- `document.getElementById()` for element selection
- `createElement()` and `appendChild()` for dynamic content
- Event listeners with `addEventListener()`
- Form data collection and validation
- Dynamic error message rendering

## Usage Instructions

### Adding an Employee

1. Enter employee name in the "Name" field
2. Enter job title in the "Title" field
3. Enter phone extension in the "Extension" field
4. Click the "Add" button
5. The new employee appears in the table below

### Deleting an Employee

1. Locate the employee you want to remove
2. Click the "Delete" button in their row
3. The employee is immediately removed from the system

### Validation

- All three fields must contain values
- Empty fields trigger red error messages
- Error messages clear when valid input is entered
