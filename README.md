### `npm start`
### `npm test`
### `npm run build`
### `npm run eject`

https://dev.to/ethand91/creating-a-react-app-with-typescript-tailwind-support-18b8
npm install -D tailwindcss postcss autoprefixer 
npx tailwindcss init -p

Next open up the created "tailwind.config.js" file and add the following to "content":
content: [
    './src/**/*.{js,jsx,ts,tsx}',
],
Next we need to add the Tailwind directives to the "src/index.css" file, add the following to the top of the file:
@tailwind base;
@tailwind components;
@tailwind utilities;