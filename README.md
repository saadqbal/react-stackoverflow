# react-stackoverflow-card

> show your stackoverflow profile details as a badge in React

[![NPM](https://img.shields.io/npm/v/react-stackoverflow-card.svg)](https://www.npmjs.com/package/react-stackoverflow-card) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)



## [Demo](https://codesandbox.io/s/react-stackoverflow-card-0tehm?file=/src/App.js)

## Install

```bash
npm install --save react-stackoverflow-card
```

## Usage

```jsx
import React from 'react'

import { StackOverflowProfile } from 'react-stackoverflow-card'
import 'react-stackoverflow-card/dist/index.css'
// id is your stackoverflow id which can be found in your profile link
const App = () => {
  return <StackOverflowProfile id='840186' containerStyle={{ backgroundColor: 'white' }} />
}

export default App
```

## License

MIT © [saadqbal](https://github.com/saadqbal)
