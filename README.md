# codetech-task1
NAME: POOJITHA N
COMPANY:CODETECH IT SOLUTIONS
ID:CT4WD3585
DOMAIN:WEB DEVELOPMENT
DURATION:4 WEEKS(1ST JULY - 1ST AUGUST,2024)



ToDo-List Web Application


Overview
This project is a simple and responsive To-Do List web application built using HTML, Bootstrap for styling, and JavaScript for functionality. It allows users to add, view, and delete tasks with a user-friendly interface. The app leverages the browser's local storage to persist tasks across sessions.

Features
Responsive Design: Uses Bootstrap to ensure the application is visually appealing and works well on various devices.
Add Tasks: Users can input a title and description for their tasks.
View Tasks: Tasks are displayed in a structured table format.
Delete Tasks: Users can remove individual tasks.
Clear All Tasks: An option to clear all tasks from the local storage.
Persistent Storage: Utilizes local storage to save tasks between sessions.

HTML Structure

Head Section
Includes meta tags for character set and viewport settings.
Links Bootstrap CSS for styling.
Sets the title of the page to "ToDo-List".


Body Section
Navigation Bar
A responsive navigation bar with links to Home, a generic link, and a dropdown menu.
Includes a search form within the navbar.
Main Container
Header (<h2>) with the text "ToDo-List".
Form for Adding To-Do Items:
Input field for the task title.
Textarea for the task description.
"Save" button to add the task.
"Clear All" button to clear all tasks from local storage.
Table for Displaying To-Do Items:
Displays the list of tasks with columns for serial number, title, description, and actions.


JavaScript Functionality
getAndUpdate()
Fetches values from the title and description fields.
Updates local storage with the new task.
Calls the update() function to refresh the displayed list of tasks.
update()
Retrieves tasks from local storage.
Updates the table body to display the current list of tasks.
Generates HTML for each task, including a delete button.
deleted(itemIndex)
Deletes a specific task based on the provided index.
Updates local storage and refreshes the displayed list.
clearStorage()
Clears all tasks from local storage.
Refreshes the displayed list.


Event Listeners
Adds an event listener to the "Save" button to call getAndUpdate() when clicked.
Initializes the display by calling update() to load existing tasks from local storage when the page loads.


CSS Styling
The body background color is set to sky blue.
The container has a peach puff background, with padding, border radius, and a box shadow for a card-like appearance.
Form groups and buttons have specific margins for spacing.
Table styling includes padding, borders, and background colors for headers.
Summary
This project provides a functional and aesthetically pleasing To-Do List application. Using Bootstrap ensures a responsive design, while JavaScript handles the addition, deletion, and persistence of tasks through local storage. This makes it a handy tool for managing daily tasks efficiently.
