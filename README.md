# Task-Management

# Task Manager Application


A responsive React-based Task Manager with CRUD functionality, filtering, and local storage persistence.

Live demo link:
https://task-management-pradeepb-c21cf9.netlify.app/

## Features

- **Full CRUD Operations**:
  - Create, Read, Update, and Delete tasks
  - View task details in modal
- **Task Status Management**:
  - Mark tasks as Completed/Pending
  - Visual status indicators (color-coded badges)
- **Advanced Filtering**:
  - Filter by: All, Completed, or Pending tasks
  - Clear filters option
- **Persistent Storage**:
  - All tasks saved to localStorage
- **User Experience**:
  - Toast notifications for all actions
  - Loading indicators during operations
  - Confirmation dialogs for deletions
- **Special Feature**:
  - One permanent task ("Welcome Task") that cannot be deleted (demonstrating protected tasks)

## Special Implementation Note

The application includes one special task titled "Welcome Task" that cannot be deleted. This demonstrates:
- Implementation of protected/undeletable tasks
- Conditional rendering of delete buttons
- Business logic for task management exceptions

