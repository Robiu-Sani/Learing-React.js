## create project with tailwindcss
1. create ----
```
   npx create-react-router@latest my-project
   cd my-project
   npm install
```
2. install tailwindcss
```
   npm install tailwindcss @tailwindcss/vite
```
3. in vite.config.js
```
import { reactRouter } from "@react-router/dev/vite";
import { defineConfig } from "vite";
import tailwindcss from "@tailwindcss/vite";
export default defineConfig({
  plugins: [
    tailwindcss(),
  ],
});
```
4. in tailwind.css
```
@import "tailwindcss";
```
5. run project
```
npm run dev
```
