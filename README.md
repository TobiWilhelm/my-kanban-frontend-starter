# Kanban Frontend

This project is a frontend application for a Kanban board, built to manage tasks and workflows visually. It allows users to add, edit, and delete items, providing a clear overview of project progress.

## Important Commands

- `npm install`: Installs project dependencies.
- `npm run dev`: Starts the development server.
- `npm run build`: Builds the project for production.
- `npm run lint`: Runs ESLint to check for code style issues.

## Technology Stack

- **React**: A JavaScript library for building user interfaces.
- **TypeScript**: A typed superset of JavaScript that compiles to plain JavaScript.
- **Vite**: A fast build tool that provides a quick development experience.
- **Tailwind CSS**: A utility-first CSS framework for rapid styling.
- **Shadcn/ui**: A collection of reusable components built with Tailwind CSS and Radix UI.

## Architecture Overview

The frontend application interacts with a REST API to manage Kanban board data. The architecture follows a component-based approach using React. Key components include:

- **KanbanBoard**: The main component that displays the columns and items.
- **KanbanItem**: Represents a single task or item on the board.
- **KanbanSheet**: A component likely used for displaying or editing item details in a sheet or modal.

The application fetches and sends data to the backend REST API for operations like adding, editing, and deleting items. The specific endpoints and data structures are defined by the API.

## Additional Information

- The project uses ESLint for code linting and follows a consistent code style.
- Project dependencies are managed with npm.
