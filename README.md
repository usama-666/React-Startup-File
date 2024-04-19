# React-Startup-File
react startup files


Es-lint configuration 

npm i --save-dev vite-plugin-eslint eslint-config-react-app eslint


Tailwind Configuration

npm create vite@latest my-project -- --template react
cd my-project

npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p

 content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],

  @tailwind base;
@tailwind components;
@tailwind utilities;
