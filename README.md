# boolString
JavaScript library for converting a string into a bool.

## Install
Using NodeJs (via npm)
```bash
npm install --save boolString
```

Using Web Brwoser (via unpkg)
```HTML
<script src="https://unpkg.com/boolString@1.0.0/index.js"></script>
```

## Example
```JavaScript
var yesString = "yes";

console.log(boolString(yesString)); // true

var noString = "no";

console.log(boolString(noString)); // false
```

## Supported Strings
Contributions are welcome to add more strings. To start, create a pull request (preferred) or an issue.

* `true`
* `yes`
* `valid`
* `on`
* `enabled`
* `enable`
* `1`

## License
boolString is licensed under the open source MIT license. View the [LICENSE](https://github.com/domkalan/boolString/blob/master/LICENSE) file for more information.