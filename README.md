# Testing React with Jest & Enzyme

## Insatalling dependencies:

```
yarn add -D enzyme enzyme-adapter-react-16 jest jest-enzyme 
```

## Configure Enzyme adapter:

#### **`setupTests.js`**
```js
import {configure} from 'enzyme'
import EnzymeAdapter from 'enzyme-adapter-react-16'

configure({
  adapter: new EnzymeAdapter(),
  disableLifecycleMethods: true
})

```