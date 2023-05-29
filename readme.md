# TS Project
A simple, pre-configured TS project to enjoy coding! Including:
- [TypeScript](https://www.typescriptlang.org/) configured for NodeJS 🔧
- [Jest](https://jestjs.io/) for testing 🧪
- [ESlint](https://eslint.org/) for static code analysis 🔍
- [Prettier](https://prettier.io/) for better formatting 🧽
- [husky](https://typicode.github.io/husky/) for improving git commits 🐶
- [dotenv](https://www.npmjs.com/package/dotenv) for getting configuration from .env file 🔐
- [nodemon](https://www.npmjs.com/package/nodemon) for easier development 🧱

I highly recommend using [Volta](https://volta.sh/) for easier toolchain management. 💫

## Installation
```bash
git clone git@github.com:mrcyna/ts-project.git
cd ts-project
cp .env.example .env
npm install
npm run start
```

## Workflow
While developing you can use nodemon to see the changes on the fly. You can simply run:
```bash
npm run dev
```

If you want to check type or format issues you can simply run:
```bash
npm run lint
```
if there is any problem you can fix that automatically by running:
```bash
npm run lint:fix
```

if you want to run tests you can simply run:
```bash
npm run test
```

if you have broken tests probably you are going to change the code multiple time, then you can keep the test running with:
```bash
npm run test:watch
```
