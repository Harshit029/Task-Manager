# Task-Manager
Task Manager In Reactjs
 Task Manager is a React-based task management app designed to help users efficiently organize, prioritize, and track their tasks. The app supports adding new tasks, setting priorities, sorting, filtering by title and priority, and marking tasks as completed. The priority levels are color-coded to provide quick visual cues, and the app also persists data in the browser’s localStorage so tasks remain available after a page refresh.

Features
Add Tasks: Create new tasks with a specified priority level (Low, Medium, High).
Search & Filter: Search tasks by title and filter based on priority.
Sort: Sort tasks by title or priority.
Completion Toggle: Mark tasks as completed, with completed tasks displayed with reduced opacity.
Persistent Storage: Task data is stored in localStorage to retain state across browser sessions.
Dynamic Priority Update: Change the priority of any task from the task list.
Setup & Installation
Prerequisites
Node.js (>=14.x) and npm should be installed on your machine.
Installation
Clone the repository:

bash
Copy code
git clone [https://github.com/Harshit029/Task-Manager](https://github.com/Harshit029/Task-Manager).git
cd modern-task-manager
Install the dependencies:

bash
Copy code
npm install
Running the Application
Start the development server:

bash
Copy code
npm start
This will start the application locally. You can access it in your browser at http://localhost:3000.

Build for Production: To create an optimized build for deployment, run:

bash
Copy code
npm run build
Assumptions
Task Structure: Each task is assumed to have a title, a completion status, and a priority level.
Task ID: The Date.now() function is used for generating unique IDs for each task.
Sorting Criteria: Sorting by title is alphabetical, and sorting by priority is based on an assigned value for each priority (High > Medium > Low).
UI Components: The design assumes access to UI components such as Input, Button, Card, and Checkbox, imported from custom modules or a component library.
