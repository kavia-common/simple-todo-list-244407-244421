# React Todo App

A minimal and responsive React todo application with a retro-inspired theme. This app allows you to add, complete, delete, and filter todos, with all data stored in your browser's localStorage. There is no backend or authentication required.

## Features

- **Add Todo**: Quickly add new todo items using the input at the top.
- **Mark Complete**: Click a checkbox to mark a todo as completed.
- **Delete Todo**: Remove todos from your list instantly.
- **Filtering**: Toggle between _All_, _Active_, and _Completed_ todos.
- **Local Storage Persistence**: Your todos persist across browser sessions.
- **Responsive & Minimal UI**: Works well on mobile and desktop, with a clean design and subtle retro theme.
- **Dark/Light Theme Switcher**: Quickly switch between light and dark mode for readability and preference.  
  _Note: To toggle theme, use the theme button at the page's top right._

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v16 or higher recommended)
- [npm](https://www.npmjs.com/)

### Installation & Setup

In the `todo_frontend` directory, run:

```bash
npm install
```

To start the development server:

```bash
npm start
```

The app will be available at [http://localhost:3000](http://localhost:3000) by default.

### Available Scripts

- `npm start`: Runs the app in development mode.
- `npm test`: Launches the test runner in interactive watch mode.
- `npm run build`: Builds the app for production to the `build` folder.

## Usage Instructions

1. **Adding a Todo**:  
   Enter text in the input field and press _Enter_ or click the add button.

2. **Completing a Todo**:  
   Click the checkbox next to a todo to mark it as completed or uncompleted.

3. **Deleting a Todo**:  
   Click the delete (🗑️) icon or button next to a todo to remove it.

4. **Filtering Todos**:  
   Use the filter buttons (All / Active / Completed) at the bottom to see only the desired subset.

5. **Theme Switcher**:  
   Use the theme toggle button at the top-right corner to switch between light and dark modes.

_All actions automatically update your local todo list and persist between browser sessions._

## Folder Structure

```
todo_frontend/
  public/       # Static files (HTML, manifest)
  src/          # Source code (React components, CSS)
  package.json  # Project config and dependencies
  README.md     # This manual
```

## Customization

You can modify the theme colors in `src/App.css`.  
Adjust styles and component structure as needed in `src/`.

## Environment Variables

_Note: For most users, customization of environment variables is not required unless deploying to a custom environment._

Default port: **3000**

## Project Details

- **Framework:** React 18
- **Frontend only**: No backend or database included.
- **Monolithic architecture**: All logic and UI handled within the frontend container.

## Learn More

- [React Documentation](https://react.dev/)
- To customize further, see `src/` for component code and CSS.

---

_Created as a clean starting point for todo apps and React UI explorations._
