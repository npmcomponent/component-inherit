*This repository is a mirror of the [component](http://component.io) module [component/inherit](http://github.com/component/inherit). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/component-inherit`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# inherit

  Prototype inheritance utility.

## Installation

```
$ component install component/inherit
```

## Example

```js
var inherit = require('inherit');

function Human() {}
function Woman() {}

inherit(Woman, Human);
```

## License

  MIT
