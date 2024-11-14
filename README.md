# Task Manager
#Overview
Task Manager is a React-based application designed to help users manage tasks efficiently with features for creating, prioritizing, and tracking progress. With an intuitive interface, users can add new tasks, set priorities, search, sort, and mark tasks as completed. The app saves all task data in localStorage, ensuring persistence across sessions.

Key Features

# 1.Add Tasks: Quickly add new tasks with options to set priority (Low, Medium, High).
# 2.Search & Filter: Filter tasks by title and sort them by priority or title for easy management.
# 3.Edit Priority: Adjust task priorities directly from the task list.
# 4.Completion Tracking: Mark tasks as completed, with visual indicators for completed tasks.
# 5.Data Persistence: Task data is stored in localStorage to remain available after page refresh

# Setup & Installation
Prerequisites
Node.js (version 14.x or later)
npm (Node Package Manager)
Installation
Clone the repository:
git clone https://github.com/Harshit029/Task-Manager
cd modern-task-manager
npm install
npm start
Build for Production: To generate an optimized build for deployment, use:
npm run build
This will create a production-ready version in the build folder.

# Application Structure & Assumptions.
# Task Object: Each task includes an id (unique identifier), title, completed status, and priority (Low, Medium, High).
# Unique Task IDs: The app uses Date.now() to generate unique task IDs. For larger applications, a more robust method may be needed.
# Sorting: Tasks are sorted alphabetically by title or by priority order (High > Medium > Low).
# UI Components: Custom UI components like Input, Button, and Card are used for a consistent, responsive design. These may be imported from component libraries or custom-built modules.
# LocalStorage for Persistence: Task data is stored locally, meaning tasks will persist until the user clears their browser’s storage.

