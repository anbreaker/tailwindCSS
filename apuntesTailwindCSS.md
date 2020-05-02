# Dependencias

-   `npm init -y`
-   `npm install tailwindcss autoprefixer postcss-cli`

# Inicializamos las herramientas instaladas:

-   `npx tailwindcss init`

# Creamos archivo de configuracion postcss.config.js

-   `touch postcss.config.js`

# Completamos script en package.json

-   `"scripts": { "build": "postcss css/tailwind.css -o public/css/styles.css"}`

# Inicializamos script para crear el css

-   `npm run build` --> genera una directorio css con su styels.css en la carpeta public
