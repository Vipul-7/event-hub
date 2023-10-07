Create and see the available tech events at the global level and expand your network.
-Previous repo with this project was deleted due to some issues so this is the new repo with the same project.

## Description

This is a simple application that allows you to create and see the available tech events. My main intention to create this project is to learn [Tanstack React Query v5](https://www.npmjs.com/package/@tanstack/react-query).

Tanstack React Query is a powerful tool for managing server state in React applications. It is a React Hooks-based library that allows you to easily manage and share server state across your entire application

I didn't use the redux for state management because react query can cache the previously fetched data and it can be used for next time if steal time is not expired so it will reduce the number of API calls and improve the performance of the application. and also we do not have to manage gloabal state to serve data to multiple components.

## Tech Stack

- ReactJS
- Tanstack React Query
- NodeJs
- expressJS
- CSS

# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
