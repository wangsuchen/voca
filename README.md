![Image](https://github.com/panzerdp/voca/raw/master/jsdoc/template/static/images/voca-logo250px.png)

**The ultimate JavaScript string library** [https://vocajs.com](https://vocajs.com)

[![travis build](https://img.shields.io/travis/panzerdp/voca.svg)](https://travis-ci.org/panzerdp/voca)
[![code coverage](https://img.shields.io/codecov/c/github/panzerdp/voca.svg)](https://codecov.io/github/panzerdp/voca)
[![sauce test status](https://saucelabs.com/buildstatus/panzerdp)](https://saucelabs.com/u/panzerdp)
[![dependencies](https://david-dm.org/panzerdp/voca.svg)](https://david-dm.org/panzerdp/voca)

Voca is a JavaScript library for manipulating strings.    

## Features

*  Provides the complete set of functions to manipulate, chop, format, escape and query strings
*  Covered by detailed and comfortable [documentation](https://vocajs.com)
*  Supports a wide range of environments: Node.js 0.10+, Chrome, Firefox, Safari 7+, Edge 13+, IE 9+
*  100% code coverage
*  No dependencies

## Documentation

See the complete documentation at [https://vocajs.com](https://vocajs.com)

## Usage
Voca can be used in various environments.

#### Node.js, Rollup, Browserify
Install the library with npm into your local modules directory:

```bash
npm install voca
```

Then in your application import the entire library:

```javascript
var v = require('voca');
v.trim(' Hello World! ');
// => 'Hello World'
v.sprintf('%s costs $%.2f', 'Coffee', 1.5);
// => 'Coffee costs $1.50'
```

Or individual functions:

```javascript
var words = require('voca/words');
words('welcome to Earth');
// => ['welcome', 'to', 'Earth']
```

#### Browser
Use `dist/voca.min.js` (minified production-ready) or `dist/voca.js` builds to load the library directly into browser's web page:

```html
<script src="path-to-scripts/voca.js" type="text/javascript"></script>
```

Then a global variable `v` is exposed:

```html
<script type="text/javascript">
  v.isBlank('  ');
  // => true
</script>
```

## Bug reports

For bug reports, documentation typos or feature requests feel free to create an [issue](https://github.com/panzerdp/voca/issues).  
Please make sure that the same problems wasn't reported already.

For general usage questions please ask on [StackOverflow](http://stackoverflow.com/questions/ask).

## Contribution

Contribution is welcome!

* Create a pull request containing bug fixes or new features. Include unit tests and keep the code coverage report near 100% (yep, perfectionism 😎)
* [Propose](https://github.com/panzerdp/voca/issues) new functions, improvements, better documentation

## Development

Visit the [development section](https://github.com/panzerdp/voca/blob/master/markdown/DEVELOPMENT.md) to find more details.


## Author

[Dmitri Pavlutin](https://rainsoft.io/about-me/)

## License

Licensed under the [MIT License](https://github.com/panzerdp/voca/blob/master/markdown/LICENSE)