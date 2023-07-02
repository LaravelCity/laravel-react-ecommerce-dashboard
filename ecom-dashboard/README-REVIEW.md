```
D:\xampp>cd htdocs

D:\xampp\htdocs>node -v
v18.12.1

D:\xampp\htdocs>npm -v
9.3.0

D:\xampp\htdocs>npm install -g create-react-app
npm WARN deprecated tar@2.2.2: This version of tar is no longer supported, and will not receive security updates. Please upgrade asap.

changed 67 packages in 21s

5 packages are looking for funding
  run `npm fund` for details

D:\xampp\htdocs>npx create-react-app ecom-dashboard

Creating a new React app in D:\xampp\htdocs\ecom-dashboard.

Installing packages. This might take a couple of minutes.
Installing react, react-dom, and react-scripts with cra-template...


added 1422 packages in 5m

226 packages are looking for funding
  run `npm fund` for details

Initialized a git repository.

Installing template dependencies using npm...

added 74 packages, and changed 1 package in 26s

235 packages are looking for funding
  run `npm fund` for details
Removing template package using npm...


removed 1 package, and audited 1496 packages in 38s

235 packages are looking for funding
  run `npm fund` for details

74 vulnerabilities (69 moderate, 5 high)

To address issues that do not require attention, run:
  npm audit fix

To address all issues (including breaking changes), run:
  npm audit fix --force

Run `npm audit` for details.

Created git commit.

Success! Created ecom-dashboard at D:\xampp\htdocs\ecom-dashboard
Inside that directory, you can run several commands:

  npm start
    Starts the development server.

  npm run build
    Bundles the app into static files for production.

  npm test
    Starts the test runner.

  npm run eject
    Removes this tool and copies build dependencies, configuration files
    and scripts into the app directory. If you do this, you can’t go back!

We suggest that you begin by typing:

  cd ecom-dashboard
  npm start

Happy hacking!

D:\xampp\htdocs>cd ecom-dashboard

D:\xampp\htdocs\ecom-dashboard>code .

D:\xampp\htdocs\ecom-dashboard>npm start

> ecom-dashboard@0.1.0 start
> react-scripts start       

(node:19788) [DEP_WEBPACK_DEV_SERVER_ON_AFTER_SETUP_MIDDLStarting the development server...

One of your dependencies, babel-preset-react-app, is importing the
"@babel/plugin-proposal-private-property-in-object" package without
declaring it in its dependencies. This is currently working because
"@babel/plugin-proposal-private-property-in-object" is already in your
node_modules folder for unrelated reasons, but it may break at any time.

babel-preset-react-app is part of the create-react-app pr
Compiled successfully!

You can now view ecom-dashboard in the browser.

  Local:            http://localhost:3000
  On Your Network:  http://172.21.208.1:3000

Note that the development build is not optimized.
To create a production build, use npm run build.

webpack compiled successfully
```
