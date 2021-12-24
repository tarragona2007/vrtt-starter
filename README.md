# 1 Install Vite + React + ts

npm init vite@latest vrtt-starter -- --template react-ts
cd vrtt-starter
npm install

# 2 Add Tailwind CSS

npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p

tailwind.config.js :

```
module.exports = {
  content: [
    "./index.html",
    "./src/**/*.{vue,js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

index.css :

```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

# 3 Then code happily

npm run dev
