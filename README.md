# to-do-list
To-Do List Application

Overview

This is a simple To-Do List application built using HTML, CSS, and JavaScript. It allows users to add, mark as completed, and delete tasks. Tasks are stored in the browser's localStorage, ensuring they persist even after refreshing the page.

Features

Add new tasks.

Mark tasks as completed by clicking on them.

Delete tasks using the delete button.

Tasks are saved in localStorage and persist across sessions.

Installation

Clone the repository or download the project files.

Open index.html in a web browser.

Usage

Enter a task in the input field.

Click the Add Task button to add it to the list.

Click on a task to toggle its completed status.

Click the Delete button to remove a task.

Code Explanation

The script listens for the DOMContentLoaded event to ensure the DOM is fully loaded before execution.

Tasks are retrieved from localStorage and rendered on page load.

When a new task is added, it is stored in an array and displayed in the UI.

Clicking on a task toggles its completion status.

Clicking the delete button removes the task from both the UI and localStorage.

Technologies Used

HTML

CSS

JavaScript

localStorage
