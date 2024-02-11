# Setup vite project

```
  npm create vite@latest

```

### Run projects

```
  npm install
  npm run dev

```

# GitHub Add Step

1

```
  git init
```

2

```
  git add .
```

3 Add message

```
  git commit -m "setup done with vite"
```

4 Creat branch then push

```
git checkout -b reactrouter

```

5

```
  git remote add origin https://github.com/har1nagle/react-router-dom-01.git
```

## Setup Tailwind CSS

1

```
  npm install -D tailwindcss postcss autoprefixer
  npx tailwindcss init -p
```

2.  add in `tailwind.config.js` file

```
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],

```

3 add in `index.css`

```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

### 1 this use for updated time than push

```
git add .

git commit -m "Added tailwind config"

git push origin reactrouter

```
