# discord_clone

## Technologies and Tools Used
    - HTML
    - Tailwind CSS
    - VS Code

## Setup
### Do the following to setup the tailwind project
    - Run the commands in terminal 
    ```
        npm install -D tailwindcss postcss autoprefixer vite
        npx tailwindcss init -p
    ```
    - You will get the following files after the above command: 
        - node_modules
        - package-lock.json
        - package.json
        - postcss.json
        - postcss.config.json
        - tailwind.config.js
    - Set `content: ["*"]` in the `tailwind.config.js` file
    - Add the following in the object of package.json
    ```
        "scripts": {
        "start": "vite" 
        }
    ```
    - In the `main.css` file, add the follwing:
    ```
        @tailwind base;
        @tailwind components;
        @tailwind utilities;
    ```
    - Link the css file in `index.html`
    - Add the fonts mising in the `main.css` file
    - Go into the `tailwind.config.js` file and set the font-family to use external fonts as:
    ```
        fontFamily:{
            Whiteny:["Whiteny"],
            Ginto:["Ginto"],
            ggSans:["ggSans"]
        }
    ```