# extractMentions
Extract @mentions from a given string

This lib does not uses regex. it automatically handles punctuation marks like "." and "," etc.

```javascript

const extractMentions = require('/path/to/extractMentions.js');

let str = `

  hello @name, welcome to @delhi!
  
`;

console.log(extractMentions(str)); // returns [{name: "name", index: 6}, {name: "delhi", index: 24}]

```
