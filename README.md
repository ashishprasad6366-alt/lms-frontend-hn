# LMS Frontend

### Setup instruction

1. Clone the project
```
    git clone https://github.com/ashishprasad6366-alt/lms-frontend-hn.git
```

2. Move into the directory
```
    cd lms-frontend-hn
```

3. install dependencies
```
    npm i
```

4. run the server
```
    npm run dev
```

### Setup instructions for tailwind

[Tail wind official instruction doc] (https://tailwindcss.com/docs/installation/using-vite)

1. Install tailwindcss
```
    npm install  tailwindcss @tailwindcss/vite
```

2. Create tailwind config file
```
    npx tailwindcss init
```

3. Add file extensions to tailwind config file n the contents property
```
    "./src/**/*.{html, js, jsx, ts, tsx}"
```

4. Add the tailwind directives at athe top of the `index.css` file
```
@import "tailwindcss";
```

### Adding plugins and dependencies

```
    npm install @reduxjs/toolkit react-redux react-router-dom react-icons react-chartjs-2 chart.js daisyui axios react-hot-toast @tailwindcss/line-clamp
```