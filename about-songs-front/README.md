# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default {
  // other rules...
  parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
  },
}
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list



### Rules of orgainizing the project

- `src` folder contains all the source code
- `src/components` folder contains all the components
- `src/components/common` folder contains all the common components that are used in the application
- `src/components/router` folder contains all the router components that are used in the application
- `src/components/layout` folder contains all the layout components that are used in the application
- `src/components/pages` folder contains all the pages components that are used in the application



- `src/pages` folder contains all the pages the differens of components and pages is that pages are the routes of the application
- `src/theme` folder contains all the theme globals and theme provider
- `src/services` folder contains all the services that are used in the application
- `src/hooks` folder contains all the custom hooks
- `src/utilities` folder contains all the utility functions generics
- `src/models` folder contains all the models that are used in the application
