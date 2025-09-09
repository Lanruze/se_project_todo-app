# Simple Todo App

The Todo app is a lightweight, interactive Todo application built with JavaScript, ES6 modules, and Object-Oriented Programming (OOP).

The app allows users to add, view, check off, and delete tasks while ensuring input validation for a clean and user-friendly experience.

## Functionality

**Further description**

A simple yet powerful Todo app designed to make managing daily tasks effortless.
Developed with JavaScript, ES6 modules, and Object-Oriented Programming (OOP) for maintainable structure.
Users can create tasks with optional due dates and see them displayed in a dynamic task list.
Each todo can be checked off when finished or removed completely with one click.
A flexible FormValidator class provides real-time error handling and input validation.
After successful submission, the form resets automatically to keep the workflow smooth.
The project highlights modular coding practices and a user-friendly interface.

**Functionality**

- Add Todos: Create new tasks with a title and optional due date.

- Unique Task IDs: Each task is automatically assigned a unique ID using the uuid package.

- Mark as Complete: Toggle task completion with a checkbox.

- Delete Tasks: Remove tasks from the list with a single click.

- Form Validation:

Prevents submission of invalid inputs.

Displays inline error messages for form fields.

Disables/enables the submit button dynamically based on input validity.

- Reset on Submit: After successfully adding a todo, the form fields reset and the submit button is disabled for a clean state.

- [Link to screenshots](https://www.canva.com/design/DAGyZZB33oQ/08W6tAWsC_oRnno8aTzywQ/edit?utm_content=DAGyZZB33oQ&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

## Technology

This project was built using modern JavaScript and web development best practices:

- JavaScript (ES6+)

Classes & OOP: Encapsulation of functionality into Todo and FormValidator classes.

Modules: Clean separation of concerns using ES modules (import/export).

- File Organization

components/ → Contains Todo.js and FormValidator.js classes.

utils/ → Holds constants.js for configuration and initial data.

pages/ → index.js (main logic) and index.css (styling).

- UUID

Imported via CDN (https://jspm.dev/uuid) to generate unique IDs for todos.

- Form Validation

Based on reusable configuration (validationConfig).

Dynamically handles input errors, button state, and reset functionality.

- HTML & CSS

Semantic HTML with <template> elements for task generation.

CSS for layout, styling, and responsive design.

## Deployment

This project is deployed on GitHub Pages:

- [Link to App](https://lanruze.github.io/se_project_todo-app/) 
