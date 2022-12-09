# Turborepo Playground

This is a playground with Turborepo.

## What's inside?

This Turborepo includes the following packages/apps:

### Apps and Packages

- `native`: a [react-native](https://reactnative.dev/) app built with [expo](https://docs.expo.dev/)
- `web`: a [Next.js](https://nextjs.org/) app built with [react-native-web](https://necolas.github.io/react-native-web/)
- `ui`: a stub [react-native](https://reactnative.dev/) component library shared by both `web` and `native` applications
- `tsconfig`: `tsconfig.json`s used throughout the monorepo

Each package/app is 100% [TypeScript](https://www.typescriptlang.org/).

### Utilities

This Turborepo has some additional tools already setup:

- [Expo](https://docs.expo.dev/) for native development
- [TypeScript](https://www.typescriptlang.org/) for static type checking
- [Prettier](https://prettier.io) for code formatting

## How to use

Run the following command:

- Clone: `git clone git@github.com:nidelson/turborepo.git {name}`
- Install: `yarn`
- Run: `yarn dev` to run all projects
- Run: `yarn dev --scope={name}` to run a single project. Running this may not show your live updates from the ui packages if they are not also running too.
