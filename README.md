# Publish React + Vite project to NPM package

This project is a simple React + Vite project that I created to learn how to publish a React + Vite project to NPM package.

The steps to publish the project to NPM package are as follows:

1. Create index.ts for exporting components.
2. Modify vite.config.ts for building the project.
3. Modify package.json for publishing the project.
4. Modify tsconfig.json for building the project.
5. Run `npm run build` to build the project.
6. Make sure "dist" folder is in the root of the project.
7. Run `npm login` and login to your NPM account.
8. Run `npm publish` to publish the project to NPM.

After finishing the steps above, you can find the package in the NPM account.
You can install the package by running `npm install your-package-name`.
