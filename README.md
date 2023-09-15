# LMS Frontend

### Setup instruction

1. Clone the project
```
    git clone https://github.com/gaurav10000/lms-frontend.git
```
2. Move inti the directory
```
    cd lms-frontend
```
3. Install dependencies 
```
    npm install
```
4. Start the project
```
    npm run dev
```


### Setup instruction for tailwind

[tailwind official instruction doc](https://tailwindcss.com/docs/installation)

1. Install tailwind
```
    npm install -D tailwindcss
```

2. Create a tailwind.config.js file
```
    npx tailwindcss init
```

3. Add file extensions to tailwind.config.js file in content
```
    "./src/**/*.{html,js,jsx,ts,tsx}"
```

4. Add the tailwind directives at the top of the `index.css` file
```
    @tailwind base;
    @tailwind components;
    @tailwind utilities;
```