# React
### installition
```
npm create vite@latest project-name -- --template react
cd project-name
npm install
```
### importanst packages
```
npm install react-router-dom localforage match-sorter sort-by
npm install -D tailwindcss postcss autoprefixer
npm i -D daisyui@latest
npm install react-icons --save
npm install react-hook-form
npm install --save react-toastify
npm install sweetalert2
npx tailwindcss init -p
npm install react-hot-toast
```
- or
```
npm install react-router-dom localforage match-sorter sort-by react-icons react-hook-form react-toastify sweetalert2 && npm install -D tailwindcss postcss autoprefixer daisyui@latest
npx tailwindcss init -p
```
#### in tailwind.config.js have to add 
```
/** @type {import('tailwindcss').Config} */
export default {
  content: ["./index.html", "./src/**/*.{js,ts,jsx,tsx}"],
  theme: {
    extend: {},
  },
  plugins: [require("daisyui")],
};
```
#### in index.css have to add 
```
@tailwind base;
@tailwind components;
@tailwind utilities;
```
### Run
``` 
npm run dev
 ```
