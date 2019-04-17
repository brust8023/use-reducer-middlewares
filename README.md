# use-reducer-middlewares
> enhance React Hooks API useReducer to apply middlewares.

[![NPM](https://img.shields.io/npm/v/use-reducer-middlewares.svg)](https://www.npmjs.com/package/use-reducer-middlewares)
[![Build Status](https://travis-ci.org/ariesjia/use-reducer-middlewares.svg?branch=master)](https://travis-ci.org/ariesjia/use-reducer-middlewares)

## Install
```bash
// use yarn
yarn add use-reducer-middlewares
// use npm
npm install use-reducer-middlewares
```

## Demo

```javascript
import useForm from 'use-reducer-middlewares'

const [state, dispatch] = useMiddleWares(reducer, initialState)([
  xxxMiddleware
]);
```