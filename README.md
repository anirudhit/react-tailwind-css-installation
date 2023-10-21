# tailwindcss Installation in React app

## Step - 1:

- Create react project using **npx** command

  ```
  npx create-react-app .

  (This command will create react app in the current folder)
  ```

## Step - 2:

- Run the react project using **npm** command

  ```
  npm run start

  (This command will start react app on default port# 3000)
  ```

## Step - 3:

- Adding **tailwindcss** to the dev dependencies

  ```
  npm install -D tailwindcss

  (This command will add tailwindcss to dev dependency)
  ```

## Step - 4:

- Initializing **tailwindcss** config js file

  ```
  npx tailwindcss init

  (This command will add tailwindcss config js file)
  ```

## Step - 5:

- Configuring the template paths

  ```
  content: [
    "./src/*.js",
  ]

  (All the JS files are added to watch the tailwindcss changes)
  ```

## Step - 6:

- Adding the Tailwind directives to **index.css**

  ```
  @tailwind base;
  @tailwind components;
  @tailwind utilities;
  ```

## Step - 7:

- Rerun the build process

  ```
  npm run start
  ```

### tailwind css documentation

- https://tailwindcss.com/docs/installation

### Video credits

- https://www.youtube.com/watch?v=L3wJe66tlBk
