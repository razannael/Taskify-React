<<<<<<< HEAD
# Taskify

Taskify is a task management application built with React and TypeScript, featuring a user-friendly drag-and-drop interface for organizing tasks.

## Features

- **Drag-and-Drop Interface**: Easily organize your tasks with a simple drag-and-drop system.
- **React and TypeScript**: Developed using the latest versions of React and TypeScript for a robust and scalable application.
- **Customizable**: Designed to be easily customizable to fit your personal or team workflow.

## Getting Started

To get started with Taskify, follow these steps:

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Install dependencies using npm:

```bash
npm install
```
## Usage

Once the development server is running, you can start using Taskify:

- **Add Tasks**: Click on the "+" button to add new tasks.
- **Drag and Drop**: Drag tasks to rearrange their order or to put them in completed tasks area.
- **Edit Tasks**: Double click on a task to edit its details.
- **Delete Tasks**: Click on the delete icon to remove a task.

## Taskify Preview

![Taskify Preview](https://github.com/razannael/Tasify/assets/127951072/e25692c2-4d7c-41aa-a285-bdb53cd3cedb)
=======
# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
   parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
   },
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
>>>>>>> 83d793c (Initial commit)
