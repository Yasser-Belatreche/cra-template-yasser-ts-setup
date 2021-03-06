# Getting Started with This React Setup Template

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app), and edited by [me](https://www.linkedin.com/in/yasser-belatreche-6b450620a/), I add different libraries that I use in every React project, like `Typescript`, `scss modules`, `storybook`, `styled-components` and `tailwindcss`. And I structure the files.

## Before Runnig the App

first make sure to install the dev dependences needed for the project by running this command :

```
npm install -D @storybook/addon-actions @storybook/addon-essentials @storybook/addon-links @storybook/builder-webpack5 @storybook/manager-webpack5 @storybook/node-logger @storybook/preset-create-react-app @storybook/react @types/styled-components autoprefixer postcss tailwindcss webpack
```

And Also add the following scripts to your `package.json` file:

```
{
  ...

  "scripts": {
    ...
    "storybook": "start-storybook -p 6006 -s public",
    "build-storybook": "build-storybook -s public"
  },

  ...
}
```

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm run storybook`

Runs the storybook and see the components.\
Open [http://localhost:6006](http://localhost:6006) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.·\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run build-storybook`

Output a static Storybook in the storybook-static directory, which can then be deployed to any static site hosting service.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.
