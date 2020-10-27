# cra-template-richards-typescript

### Richard's TypeScript template for [Create React App](https://github.com/facebook/create-react-app). Same as cra-template-typescript but better :)!

## Differences to cra-template-typescript are:

 - `build` directory is also copied to `output`, this is helpful for some build systems.
 - The `homepage` property is package.json is set to `"."`.
 - Does not include the placeholder files: logo.svg, robots.txt, App.css, App.test.tsx, reportWebVitals.ts.
 - App.tsx and index.html are stripped back, they have no visible content.
 - Indenting is with tabs not spaces (with .editorconfig).

To use this template, add `--template richards-typescript` when creating a new app.

For example:

```sh
npx create-react-app my-app --template richards-typescript

# or

yarn create react-app my-app --template richards-typescript
```

For more information, please refer to:

- [Getting Started](https://create-react-app.dev/docs/getting-started) – How to create a new app.
- [User Guide](https://create-react-app.dev) – How to develop apps bootstrapped with Create React App.