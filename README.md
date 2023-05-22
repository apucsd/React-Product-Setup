

#### React-router

```http
 npm create vite@latest name-of-your-project -- --template react
 
```
```http
cd <your new project directory>
 
```
```http
npm install react-router-dom localforage match-sorter sort-by
 
```
#### Tailwindcss setup

```http
 npm install -D tailwindcss postcss autoprefixer
 npx tailwindcss init -p
 
```
```http
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ]
 
```
```http
  @tailwind base;
@tailwind components;
@tailwind utilities;
```
#### DaisyUI setup
```http
npm i daisyui
```
#### DaisyUI setup
```http
 plugins: [require("daisyui")],
```











#### React router others setup


```http
import {
  createBrowserRouter,
  RouterProvider,
} from "react-router-dom";
 
```
```http
const router = createBrowserRouter([
  {
    path: "/",
    element: <div>Hello world!</div>,
  },
]);
 
```
```http
 <RouterProvider router={router} />
 
```


