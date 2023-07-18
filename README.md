## Features

- 🔩 **Easily Customizable**
- 🕊 **Lightweight** - _less than 5kb including styles_
- ✅ **Accessible**

## Installation

#### With yarn

```sh
yarn add garage
```

#### With NPM

```sh
npm install garage
```

## Getting Started

Add the Garage to your app first. It will take care of all your states. Now you can access your states from anywhere!

```jsx
import { Garage, createStore } from 'garage';
import App from './App';

const store = createStore();

const Index = () => {
  return (
    <Garage store={store}>
      <App/>
    </Garage>
  );
};
```

## Documentation

Find the full API reference on [official documentation](https://npm-garage.com/docs).