## React Boiler Plate ##


### Use this for new React Projects ###


**Packages**

- **Yarn**
- **Babel Core, Cli, Loader, Preset-Env, Reset-React, Transform Class Properties**
- **Webpack Core, Cli, Dev-Server, css-loader**
- **Live Server -- but Webpack Dev-Server Preferred**
- **Node-Sass**
- **Normalize.css**
- **React Dom, Modal**
- **Validator**


**Scripts**

- **"serve-not-used":** "live-server public/",
- **"build-babel-not-used":** "babel src/app.js --out-file=public/scripts/app.js --presets=env,react --watch",
- **"build-not-used":** "webpack --watch",
- **"build":** "webpack --mode development",
- **"dev-server":** "webpack-dev-server  --mode development"



**Using to create new project and put new project in Git**

- Download 
- Rename Directory name from **React-Boilerpage** to your project
- Remove **.git** directory inside project 
- Inside run **git init**
- After run **git remote add origin <name of git project"**  Example:  **git@gitlab.bop.gov:raymond-sandbox/code-examples/javascript-react/expensify-app.git**
- Then run 
 + **git add.**  
 + **git commint -m "My new project"**
 + **git push --set-upstream origin master**
- Project is now in git


**Run for the first time**

- Run **yarn install** - to install all Node dependencies
 + If you like **NPM** you can use that instead
- Change **name** varible in **package.json**
- Change **title* in **public/index.html**
- Run **yarn run dev-server** This will start the webpack dev server along with converting ES6 to ES6 and running SASS
- Goto localhost:8080 to see changes, anytime you add something webpack will run 



**Notes**

- The only script you need to run is the **yarn run dev-server** The others are there if you want.
yar






 

