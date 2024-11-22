# Node.js + TypeScript + Express Boilerplate

A lightweight boilerplate to quickly set up a Node.js application using TypeScript and Express, equipped with hot-reloading, linting, and code formatting.

## Project Overview

This boilerplate provides a robust foundation for building server-side applications with:

- **TypeScript** for type-safe development.
- **Express** for web server functionality.
- **Nodemon** for hot-reloading during development.
- **ESLint** and **Prettier** for linting and code formatting.

---

## Getting Started

Follow these steps to get the application up and running:

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/your-repository-name.git
   cd your-repository-name

   ```

1. Install the necessary dependencies:

   ```bash
   npm install
   ```

## Build and Start the Application

To start the application with live-reload during development, run:

```bash
npm run dev
```

To build and run the compiled application (for production or testing):

```bash
npm start
```

## Project Structure

- **src/**: Contains TypeScript source files for the application.
  - `index.ts`: Entry point of the application.
- **dist/**: Compiled JavaScript files after building the TypeScript source.
- **package.json**: Dependencies and scripts for running, building, and developing the app.
- **tsconfig.json**: TypeScript configuration for the compiler options.
- **nodemon.json**: Configuration for Nodemon to watch `.ts` files.
