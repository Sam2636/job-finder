 ## create 
 `npm create vite@latest`
    select title 'jobsearch'
  `cd jobsearch`
  `npm install`
  `npm run dev`  

## I have deleted assets and removed app.css and renamed the title

## Add google fonts to index.css file 

## setting up tailwind css 
`npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p`

## check this site for vite tailwind config

`https://tailwindcss.com/docs/guides/vite`

## go to tailwind.config.js file & add this content
`  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],`

## adding tailwind css to inde.css

`@tailwind base;
@tailwind components;
@tailwind utilities;`