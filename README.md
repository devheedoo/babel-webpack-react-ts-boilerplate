# babel-webpack-react-ts-boilerplate

## Config

- Yarn
- Babel
- Webpack
- React
- TypeScript

## Install

```bash
$ yarn install
```

## Build

```bash
$ yarn build
```

## Start (develop)

```bash
$ yarn start
```

## How to make this boilerplate


### 1. Cloning empty repository from GitHub

```bash
$ git clone https://github.com/devheedoo/babel-webpack-react-ts-boilerplate.git
```

### 2. Initialize with Yarn

```bash
$ yarn init -y
```

### 3. Add dependencies: Babel, Webpack and React

```bash
$ yarn add -D react react-dom
$ yarn add -D webpack webpack-cli webpack-dev-server html-webpack-plugin
$ yarn add -D babel-loader @babel/cli @babel/core @babel/plugin-proposal-class-properties @babel/preset-env @babel/preset-react
$ yarn add @babel/polyfill
```

### 4. Add dependencies: TypeScript

```bash
$ yarn add -D typescript @babel/preset-typescript source-map-loader
$ yarn add -D @types/react @types/react-dom @types/webpack-env
```

### 5. Make and edit config files: Babel, Webpack and TypeScript
- .babelrc
- webpack.config.js
- tsconfig.json

### 6. Make basic project structure
- public/index.html
- public/favicon.ico
- src/components/App.tsx
- src/index.tsx

### 7. Clean up...
- .gitignore
- README.md

### References

- [React 빌드(webpack) 환경 직접 구성하기(without CRA)](https://p-iknow.netlify.com/front-end/react-webpack-config)
- [TypeScript With Babel: A Beautiful Marriage](https://iamturns.com/typescript-babel/)
