# ThreeJSTemplete
Three JS project setup with webpack, jest and firebase.

A ready made project for THREE.JS for typescript, with built in commands to quickly test, run, and build for quick proeject setup.
made for beginners who want to get working in THREE JS immediately.

# Prerequisites 

- Install npm, see https://www.npmjs.com/get-npm. 
- (firebase only) Setup a firebase project.  https://firebase.google.com/docs/web/setup

# Setup

1. "npm install".  Installs npm modules required for  the project
1. (firebase only) firebase init 

# commands

- "npm test" runs all jest scripts in the "./ts/tests/" folder; for more information on writing test scripts with jest see https://jestjs.io/
- "npm run"  locally hosts the project and runs it at localhost:8080. should open automatically in browser.
- "npm run build" builds the project into a minified index.js and html script in the "dist" folder.
  - (firebase only) and deploys the project to the attached firebase project. to disable open "package.json" and remove "&& firebase deploy" from "build" script.
