## new-text (a.k.a. format-text)
[![npm Package Version](https://img.shields.io/npm/v/new-format.js.svg?maxAge=2592000)](https://www.npmjs.com/package/new-format.js)

String formatting library inspired from Python

### Install

```bash
$ npm install new-format.js
```

### Usage

```js
format = require('new-format.js')

format('Hello {0}. The weather is currently {1}°.', 'Kitty', '67')
// => Hello Kitty. The weather is currently 67°.

format('Hello {name}, The weather is currently {degree}°', { name:'Kitty', degree: 67 })
// => Hello Kitty. The weather is currently 67°.
```

![](https://dl.dropbox.com/s/9q2p5mrqnajys22/npmel.jpg?token_hash=AAHqttN9DiGl63ma8KRw-G0cdalaiMzrvrOPGnOfDslDjw)
