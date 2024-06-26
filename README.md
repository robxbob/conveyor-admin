# Conveyor Admin

Conveyor Admin provides a functional UI to interact with GraphQL APIs generated by the [Magql](https://github.com/autoinvent/magql) library. It implements the comprehensive UI components in [autoinvent/conveyor](https://github.com/autoinvent/conveyor) to provide an intuitive and user-friendly interface for performing CRUD (Create, Read, Update, Delete) operations on your GraphQL data.

## Features

- **Automatic UI Generation:** Conveyor automatically introspects your GraphQL schema and generates a UI that corresponds to your data structure. This includes forms for data entry, tables for data viewing, and even more complex UI structures for nested or related data.

## Prerequisites

Before using Conveyor, you need to have a GraphQL API generated by the Magql library. Magql provides a robust, flexible, and easy-to-use way to create a GraphQL API from your existing data.

## Installation
```bash
pnpm install @autoinvent/conveyor
```

## Scripts

- `pnpm run example` - start a development server for testing the conveyor library with hot reload.
- `pnpm build` - build library for production. The generated files will be on the `dist` folder. `pnpm pack` will package these files into a tarball for install.
- `pnpm preview` - locally preview the production build.
- `pnpm test` - run tests in watch mode.
- `pnpm test:ci` - run tests once without watch mode.
- `pnpm test:ui` - run tests with ui.
- `pnpm format` - format all files with Rome.
- `pnpm lint` - runs TypeScript, Rome and Stylelint.
- `pnpm validate` - runs `lint`, `test:ci`.
