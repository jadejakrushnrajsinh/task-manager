# Task Manager

## Overview

Task Manager is a simple, frontend-only web application for managing tasks. It allows users to add, edit, and delete tasks directly in the browser, with data persisted using localStorage. This is a basic implementation built with HTML, CSS, and JavaScript, serving as a foundation for a more robust full-stack application.

## Features

- **Add Tasks**: Input new tasks and add them to the list.
- **Edit Tasks**: Modify existing tasks.
- **Delete Tasks**: Remove tasks from the list.
- **Local Persistence**: Tasks are saved in the browser's localStorage, so they persist across sessions.
- **Responsive UI**: Basic styling for a clean user experience.

## Tech Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Storage**: Browser localStorage
- **No Backend**: Currently frontend-only; future plans include Express.js and MongoDB integration.

## Setup and Installation

1. **Clone the Repository**:

   ```
   git clone https://github.com/jadejakrushnrajsinh/task-manager.git
   cd task-manager
   ```

2. **Run the Application**:

   - Open `index.html` in any modern web browser (e.g., Chrome, Firefox).
   - No additional setup required since it's static.

3. **Development**:
   - Edit `index.html` for UI changes.
   - Tasks are automatically saved to localStorage.

## Usage

- Navigate to `index.html` in your browser.
- Use the input field to add tasks.
- Click on a task to edit it.
- Use the delete button to remove tasks.

## Planned Improvements

Based on the project TODO:

- Add backend with Express.js and MongoDB for persistent storage.
- Implement user authentication for multi-user support.
- Add input validation and security features (e.g., CSRF protection).
- Enhance error handling.
- Add unit and integration tests.
- Introduce advanced features: task categories, priorities, due dates, and notifications.
- Refactor code for better modularity.
- Add deployment configuration (e.g., for Netlify or Vercel).

## Contributing

Feel free to fork the repository and submit pull requests for improvements.

## License

This project is open-source and available under the MIT License.
