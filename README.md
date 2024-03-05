# TodoList Application

# Overview
- This TodoList application allows users to manage their tasks effectively. Users can add, delete, and mark tasks as completed. The application provides a summary of the total number of todos and allows users to delete all completed todos with ease.

# Features
- Add Todo: Users can add new todos by typing in the input field and clicking the "Add" button.

- Delete Todo: Users can delete individual todos by clicking the delete button associated with each todo item.

- Mark Todo as Completed: Users can mark todos as completed by clicking the checkbox associated with each todo item.

- Delete All Completed: Users can delete all completed todos at once by clicking the "Delete all completed" button in the summary section.

# Components

   AddTodoForm Component:
- This component renders an input field and a button for adding new todos.
- Users can input their todo task and click the button to add it to the list.

 TodoList Component:
- This component displays the list of todos.
- Each todo item is displayed with a checkbox, title, and delete button.
- Todos are sorted with completed ones at the bottom.

 TodoItem Component:

- This component represents an individual todo item.
- It displays a checkbox, title, and delete button for each todo.
- Users can mark todos as completed or delete them individually.

  TodoSummary Component:

- This component provides a summary of todos.
- It displays the total number of completed todos and total todos.
- If there are completed todos, a button is provided to delete all completed todos.
  
# Usage
Adding a Todo:
- Type your todo task in the input field.
- Press the "Add" button to add the todo to the list.
- Completing a Todo:
-Click the checkbox next to the todo item to mark it as completed.

Deleting a Todo:
- Click the delete button next to the todo item to remove it from the list.
- Deleting All Completed Todos:
- Click the "Delete all completed" button in the summary section to remove all completed todos from the list.
  
# Getting Started

- To run the TodoList application locally:
- Clone this repository.
- Install dependencies using npm install.
- Run the application using npm start.
- Access the application in your browser at http://localhost:3000.
  
# Technology Stack
- React: Frontend library for building user interfaces.
- TypeScript: Typed superset of JavaScript for improved developer experience.
- Tailwind CSS: Utility-first CSS framework for styling components.
- localStorage: HTML5 web storage for persisting todo data.
