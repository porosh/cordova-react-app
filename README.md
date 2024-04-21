How to setup react into cordova app

1. Create new reactjs project
2. Create new cordova project
3. copy public and src dirs from react project to cordova project
4. Merge package.json file. Copy dependencies, scripts and browserslist from package.json file of reactjs project into cordova project
5. In cordova project, run npm install and npm start to verify that everything is working.
6. Copy meta tags from www/index.html into public/index.html
7. add cordova.js script just before </body> tag in public/index.html
