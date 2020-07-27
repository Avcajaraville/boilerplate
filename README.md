# HTML, JS & SASS boilerplate

This project is a boilerplate for frontend development.

Provides tools for developing and shipping a static site.

## Features

- Compile and transpile ES6 JS code via babel.
- Testing suite via jest with code coverage.
- Compiles SASS files into a CSS file.
- Development and production scripts.
- Prettify code.
- Linting code.

## Scripts

To run these scripts, you need to:
1. `npm install`: to install all the required dependencies.
1. `npm run [script_name]`: where script name is one of:
    - `build`: build all assets. Will generate an `index.html` file inside the `dist` folder, with all assets (CSS & JS) already minified. This is the script you want to use when deploying/building.
    - `dev`: will start `webpack-dev-server` with livereload and sourcemaps ready to be used while developing. This is the script you want to use when developing.
    - `lint`: JS linter tool using `eslint`.
    - `prettier`: prettify all your code using `prettier`.
    - `test`: run all test files (files containing `*.spec.js` extension) and generate a coverage report under `coverage` folder. It's done via `jest`.
    - `test:watch`: same as before but watching for changes.
