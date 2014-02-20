*This repository is a mirror of the [component](http://component.io) module [then/is-promise](http://github.com/then/is-promise). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/then-is-promise`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
<a href="http://promises-aplus.github.com/promises-spec"><img src="http://promises-aplus.github.com/promises-spec/assets/logo-small.png" align="right" /></a>
# is-promise

  Test whether an object looks like a promises-a+ promise

## Installation

  Client:

    $ component install then/is-promise

  Server:

    $ npm install is-promise

## API

```javascript
var isPromise = require('is-promise');

isPromise({then:function () {...}});//=>true
isPromise(null);//=>false
isPromise({});//=>false
isPromise({then: true})//=>false
```

## License

  MIT
