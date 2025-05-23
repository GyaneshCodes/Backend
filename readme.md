# Backend Course
A backend course that covers the basics of backend development, including REST APIs, databases, and authentication. This will be a comprehensive guide to building a backend application from scratch. It will teach you how to set up a server, create routes, connect to a database, and implement authentication. The course will also cover best practices for building scalable and maintainable backend applications.

The course teach you to take a professional approach to backend development, including how to structure your code, write tests, and deploy your application. By the end of the course, you will have a solid understanding of backend development and be able to build your own backend applications.

## Some links:

- [Models link](https://app.eraser.io/workspace/YtPqZ1VogxGy1jzIDkzj)

## Folder Structure

Here is a professional backend project folder and file structure overview:

- **Root Folder**
  - `package.json` — Project metadata and dependencies
  - `.gitignore` — Files/folders to exclude from Git
  - `.env` — Environment variables (not pushed to Git)
  - `.env.sample` — Sample env file for others
  - `README.md` — Project documentation

- **Public Folder**
  - `public/temp/` — Temporary files (tracked with a `.gitkeep`)

- **Source Folder (`src/`)**
  - `index.js` — Entry point of the application
  - `app.js` — Main application setup (Express, middleware)
  - constants.js — Constants used throughout the app
  - `controllers/` — Business logic functions
  - `db/` — Database connection logic
  - `middlewares/` — Middleware functions (e.g., auth checks)
  - `models/` — Data models/schema definitions
  - `routes/` — API route definitions
  - `utils/` — Utility/helper functions

- **Config Files**
  - `.prettierrc` — Prettier code formatting config
  - `.prettierignore` — Files to ignore for Prettier

- **Node Modules**
  - `node_modules/` — Installed packages (ignored in Git)

This structure supports modular, maintainable, and scalable backend development with clear separation of concerns.