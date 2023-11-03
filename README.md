# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh


1. Install Vite globally (done so don’t need to do every time) Vite is a new frontend build tool that aims to improve the developer experience for development with the local machine, and for the build of optimized assets for production (go live).
2. create-vite my-react-app --template react (change my-react-app to the name of the project)
3. cd my-react-app
4. Use the command yarn to install dependencies
5. Use yarn dev to start the development server


1. Creación proyecto React con Vite

documentación: https://es.vitejs.dev/guide/

comando: npm create vite@latest my-react-app -- --template react​


En cada proyecto
https://tailwindcss.com/docs/installation

usar el Vite config

https://tailwindcss.com/docs/guides/vite

3. Actualiar archivo: tailwind.config.js

  content: [    "./index.html",    "./src/**/*.{js,ts,jsx,tsx}",  ],


4. Actualizar archivo index.css o styles.css (dentro de la carpeta src) con:

@tailwind base;
@tailwind components;
@tailwind utilities;# my-first-react-app
