# Task Manager with React + Vite

This project is a simple task manager application built with React and Vite. It allows users to add, view, and manage tasks.

> This project's development is instructed by [Felipe Rocha](https://github.com/felipemotarocha) in his YouTube channel's video [Curso de React para Completos Iniciantes [2024]](https://www.youtube.com/watch?v=2RWsLmu8yVc&t=237s).

## Features

- Add new tasks with a title and description
- Mark tasks as completed
- Delete tasks
- View task details
- Persistent storage using `localStorage`
- Responsive design with Tailwind CSS

## Project Structure

```bash
.
├── .gitignore
├── eslint.config.js
├── index.html
├── package.json
├── public/
├── README.md
├── src/
│   ├── App.css
│   ├── App.jsx
│   ├── assets/
│   ├── components/
│   │   ├── AddTask.jsx
│   │   ├── Button.jsx
│   │   ├── Input.jsx
│   │   ├── Tasks.jsx
│   │   ├── Title.jsx
│   ├── index.css
│   ├── main.jsx
│   ├── pages/
│   │   ├── TaskPage.jsx
│   ├── styles.css
├── vite.config.js
```

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/sabrinmoura/curso-react-yt
    cd <repository-directory>
    ```

2. Install dependencies:
    ```sh
    npm install
    ```

## Development

To start the development server with hot module replacement:

```sh
npm run dev
```

## Build

To build the project for production:

```sh
npm run build
```

## Preview

To preview the production build:

```sh
npm run preview
```

## Linting

To run ESLint:

```sh
npm run lint
```

## Dependencies

- [React](https://reactjs.org/)
- [Vite](https://vitejs.dev/)
- [React Router](https://reactrouter.com/)
- [Tailwind CSS](https://tailwindcss.com/)
- [UUID](https://www.npmjs.com/package/uuid)
- [Lucide React](https://lucide.dev/)

## ESLint Configuration

The project uses ESLint with the following plugins:

- [eslint-plugin-react](https://github.com/yannickcr/eslint-plugin-react)
- [eslint-plugin-react-hooks](https://github.com/facebook/react/tree/main/packages/eslint-plugin-react-hooks)
- [eslint-plugin-react-refresh](https://github.com/facebook/react/tree/main/packages/eslint-plugin-react-refresh)

