# viteWithTailwindCss
# react vite create
# create project....
1.npm create vite@latest my-project -- --template react
cd my-project
# tailwindcss use command....
2. npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
# tailwind.config.js
2./** @type {import('tailwindcss').Config} */
export default {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
# index.css use...
@tailwind base;
@tailwind components;
@tailwind utilities;
# App.jsx use code...
3.export default function App() {
  return (
    <h1 className="text-3xl font-bold underline">
      Hello world!
    </h1>
  )
}
