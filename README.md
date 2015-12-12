# remove-reactid-attributes

A simple regex to remove `reactid` attributes.

```js
var REGEX_REMOVE_IDS = /\s?data-reactid="[^"]+"/g;

'Any HTML generated with React'.replace(REGEX_REMOVE_IDS, '');
```

Available online at https://maxcnunes.github.io/remove-reactid-attributes.
