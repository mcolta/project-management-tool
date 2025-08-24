# Project Management App

This is a simple project management application built as part of the **Understanding TypeScript** course on Udemy. The app demonstrates core TypeScript concepts, including classes, interfaces, decorators, and modules, while implementing drag-and-drop functionality for managing projects.

## Features

- Add new projects with title, description, and number of people.
- Categorize projects as "Active" or "Finished."
- Drag and drop projects between categories.
- Validation for user inputs.

## Project Structure

The project is organized into the following directories:

- **src/components/**: Contains reusable UI components like `ProjectInput`, `ProjectList`, and `ProjectItem`.
- **src/models/**: Defines TypeScript models and interfaces for `Project` and drag-and-drop functionality.
- **src/state/**: Implements state management for projects.
- **src/utils/**: Includes utility functions like input validation.
- **src/decorators/**: Contains the `autobind` decorator for method binding.

## Technologies Used

- TypeScript
- Webpack
- HTML/CSS

## Getting Started

1. Clone the repository.
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the development server:
   ```sh
   npm start
   ```
