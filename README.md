# github-todo-app

### TODO App

This HTML, CSS, and JavaScript code represent a simple To-Do application that allows users to add, edit, and delete tasks. Below is a breakdown of the files and functionalities:

### HTML (`index.html`)

- **External Libraries**: The HTML file imports external libraries like Bootstrap and Font Awesome for styling and functionality.
- **Structure**: Defines the basic structure of the application, including a form for adding new tasks and a section to display existing tasks.

### CSS (`styles.css`)

- **Styling**: This file contains custom styles to enhance the visual presentation of the application. It may include styles for layout, fonts, colors, and other visual elements.

### JavaScript (`main.js`)

- **Event Listeners**: Listens for events such as form submission and button clicks to trigger specific actions.
- **Form Validation**: Ensures that the task title is not empty before adding it to the list.
- **Data Management**: Manages the tasks data using localStorage to persist data across sessions.
- **Task Operations**: Allows users to add, edit, and delete tasks dynamically without page reload.
  
### Functionality Overview:

1. **Adding Tasks**: Users can add tasks by filling out the form with a title, due date, and description, then clicking the "Add" button.
2. **Validation**: Task title cannot be left blank. An error message will display if the title field is empty.
3. **Editing Tasks**: Users can edit tasks by clicking the edit icon next to each task. This action opens the form modal with the task details pre-filled for editing.
4. **Deleting Tasks**: Users can delete tasks by clicking the trash icon next to each task.
5. **Local Storage**: Tasks data is stored locally using the browser's localStorage API, allowing data persistence across sessions.

### How to Use:

1. Download or clone the repository to your local machine.
2. Open the `index.html` file in a web browser.
3. Start adding, editing, and deleting tasks as needed.

### Dependencies:

- Bootstrap v5.1.3: Provides styling and layout components.
- Font Awesome v5.15.4: Adds icons for a better user experience.

### Compatibility:

The application is designed to work on modern web browsers that support HTML5, CSS3, and ECMAScript 6 (ES6) standards.

Thank you for using the TODO App!