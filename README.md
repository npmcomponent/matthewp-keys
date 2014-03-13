*This repository is a mirror of the [component](http://component.io) module [matthewp/keys](http://github.com/matthewp/keys). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/matthewp-keys`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# keys

  Cross-browser Object.keys

## Installation

**keys** is meant to be used as a [component](https://github.com/component/component).

    $ component install matthewp/keys

## API

#### keys(obj)

```javascript
keys({foo: 'bar'});

> [ 'foo' ]
```

Falls back to ES5 Object.keys if the browser supports it.

## Dependencies

None.