# cra-template-yasser-ts-setup

This is an official Typscript template for [Create React App](https://github.com/facebook/create-react-app).

To use It you need to specify the template name when creating a react app using CRA like that :

```
npx create-react-app myapp --template yasser-ts-setup
```

After the installation complete don't forget to install the dev dependences by running this command:

```
npm install -D @storybook/addon-actions @storybook/addon-essentials @storybook/addon-links @storybook/builder-webpack5 @storybook/manager-webpack5 @storybook/node-logger @storybook/preset-create-react-app @storybook/react @types/styled-components autoprefixer postcss tailwindcss webpack
```

And Also add the following scripts to you package.json file:

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

For more information about CRA, please refer to:

- [Getting Started](https://create-react-app.dev/docs/getting-started) – How to create a new app.
- [User Guide](https://create-react-app.dev) – How to develop apps bootstrapped with Create React App.

Developer Contact:

- [linkedIn](https://www.linkedin.com/in/yasser-belatreche-6b450620a/)
- [twitter](https://twitter.com/YasserBelatrec1)

> For more information about this template, please open the template directory and read the README file, And in case you wanna clone it directly you can refer to [this repository](https://github.com/Yasser-Belatreche/react-typescript-project-setup.git)
