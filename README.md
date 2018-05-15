# wordypass
Word-Based Password Generator

## [Live Version](https://ahmednooor.github.io/wordypass)

### Installation

> with `npm`

```
npm i wordypass --save
```

> with `yarn`

```
yarn add wordypass
```

### Usage

```javascript
const WordyPass = require('wordypass'); // if on nodejs

const wordyPass = new WordyPass();

console.log(wordyPass.generate(8));
console.log(wordyPass.generate(12));
console.log(wordyPass.generate(16));
console.log(wordyPass.generate(20));
console.log(wordyPass.generate(24));
```

### Credits

* Words List: https://gist.github.com/deekayen/4148741
