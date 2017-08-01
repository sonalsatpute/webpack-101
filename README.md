# webpack-101
learn webpack 

# What is webpack?

- Module Bundler
- Custom files Or NPM Installed
- Generate static accests 
- Extend with plugins and loaders

# Command

- npm init //this will create package.json
- npm i -D webpack //this will install local webpack depencies 
- npm view webpack version //tell version of webpack
- npm view webpack versions //tell last 20 version of webpack
- npm view webpack versions -json //tell all versions of webpack

# Bundle
- webpack .\src\app.js .\dist\app.bundle.js //this will create the bundle file inside dist folder

- webpack .\src\app.js .\dist\app.bundle.js -p //this will create the minified bundle file inside dist folder

- webpack .\src\app.js .\dist\bundle.app.js -p --watch //this will watch for any changes and create the bundle 

# webpack config
- npm run dev // run the script from package.json

