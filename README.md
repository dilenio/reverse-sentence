# reverse-sentence

Reverses the words of a sentence.

## Install

```sh
npm install @dilenio/reverse-sentence
```

## API

```js
require("reverse-sentence") => function
reverse(sentence) => string
```

## Example

```js
const reverseSentence = require('reverse-sentence');

const sentence = 'Hello Dilenio!';

const reversed = reverseSentence(sentence);

console.log(reversed); // Dilenio! Hello
```

## License

MIT
