## Boilerplate for custom Server side rendered react app with EJS and express with Hot module replacement

## Technology stack

### Server side
 * Express
 * EJS
 * Webpack
### Client side
 * React

### Steps to run
 1. Clone the repo
 2. npm install
 3. npm start
 4. open http://localhost:4000/ to see your app

### Structure
```
    ssr-hot-reloading (your root)
    ├── readme.md
    ├── node_modules
    ├── package.json
    ├── webpack.config.js
    ├── LICENSE
    ├── .gitignore
    ├── client (all client side code goes here)
    │    ├── index.js (client entry point)
    │    └── components (all UI components)
    │         ├── card.scss
    │         └── Cards.js
    ├── server (all client side code goes here)
    │   └── index.js (server side entry point. Express server runs here.)
    ├── views (server side rendered views go here. Here you will include the bundle or other dependencies)
        └── index.ejs
```


### In Action
¸![ezgif com-gif-maker](https://user-images.githubusercontent.com/10725893/119511329-f0a12e00-bd8f-11eb-8ffd-5fa2e2f83407.gif)
