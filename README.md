# Monorepo

This project is a collaboration strategy where all the repositories are inside the same GitHub repo. The dependency management is handled by yarn workspaces. The multitasking, the dependency injection, and the build strategy are handled by Lerna.

## Main files
The availables scripts for the app can be found in the `package.json`. All the applications are inside the `/packages` folder.

### Bootstrap

1. Every app should be started from the root folder.
2. Yarn is the required package manager.
3. Every package needs to have a `build` and `start` scripts.

## Get started

1. `yarn`
2. `yarn bootstrap`
3. To start everything `yarn start`