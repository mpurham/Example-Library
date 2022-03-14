# Example Library 

This package shows an example of how to create custom library and use them in your scripts via Polypad. 

## Usage

The `myModule` has 3 string operations.

1. downcase
2. uppercase
3. camelCase

In your main script file you are able to import those functions using the `require` keyword.

```javascript
const { downcase, camelCase, uppercase } = require('@polypad/myModule')
```

In the main function you can call the above using:

```javascript
function main(input) {
    input.text = uppercase(input.text);
}
```

## Features and compatability

Simply `downcase`, `uppercase`, or `camelCase` text;

## Contributing

Any pull requests with bugfixes or efficiency improvements is greatly appreciated.
