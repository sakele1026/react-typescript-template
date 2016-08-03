This is a template for creating new React+Typescript projects, based on [create-react-app](https://github.com/facebookincubator/create-react-app) from Facebook. It will be kept up to date with the changes being made there. The main differences are:
- No Babel
- No eslint
- Typescript
- tslint

## Folder Structure

```
my-app/
  README.md
  index.html
  favicon.ico
  node_modules/
  package.json
  src/
    App.css
    App.js
    index.css
    index.js
    logo.svg
```

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

### `npm run clean`

Rimraf the build folder.
