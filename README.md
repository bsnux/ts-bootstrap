# TypeScript bootstraping

Simple skeleton for creating TS applications for Node.js

## Commands executed to create and configure this project

```
npm init
npm i ts-loader --save-dev
npx tsc --init
npm install webpack webpack-cli --save-dev
npm i chalk
npm i @types/chalk
```

## Creating bundle ready for distribution

Directly from `webpack` command:

```
node_modules/webpack/bin/webpack.js --mode=production
```

Using `npm`:

```
npm run dist
```


## Running the bundle everywhere where Node.js is installed

```
node dist/bundle.js
```
