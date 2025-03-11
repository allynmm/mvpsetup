# Tech Stack
Webpack, Babel, Eslint
JavaScript/TypeScript, React/Next.js, CSS/HTML/Tailwind 
Node.js, Express, MySQL/PostgreSQL

# Setup your MVP
I. Setup Webpack (bundler)
  a. run `npm init -y` to create package.json with minimal setup
  b. install locally -> `--save-dev webpack`
  c. add build script to package.json -> 
  d. install cli -> `npm install --save-dev webpack-cli`

II. Setup Babel (transpiler)
  a. run `npm install --save-dev @babel/core @babel/cli`
  b. replace build
  c. run `npm install @babel/preset-env --save-dev`
  d. create babel.config.json file
  e. add ```{ "presets": ["@babel/preset-env"] }``` to babel.config.json

III. Setup Eslint 
  a. run `npm init @eslint/config@latest` and answer prompts

IV. Install PostgreSQL on local machine
*MacOS instructions*
  a. run `brew install postgresql@16` (16 is currently the latest stable version)

V. Install dependencies
  A. Next.js
    1. run `npm install next@latest react@latest react-dom@latest` to install manually
  B. Express.js
    1. run `npm install express`
  C. TailwindCSS
    1. run `npm install tailwindcss @tailwindcss/vite`