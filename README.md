
# px-datetime-field [![Build Status](https://travis-ci.org/PredixDev/px-datetime-field.svg?branch=master)](https://travis-ci.org/PredixDev/px-datetime-field)

## Overview

`Px-datetime-field` is a Predix UI component which allows the user to select a date and time precisely to the second or millisecond. 

## Getting Started

Read https://github.com/pages/PX/technical-principles/

From the component's directory...

```
$ npm install
$ bower install
$ gulp sass
```

### API and examples

https://predixdev.github.io/px-datetime-field/

### LiveReload

By default gulp serve is configured to enable LiveReload and will be watching for modifications in your root directory as well as `/css`.

Your browser will also need to have the LiveReload extension installed and enabled. For instructions on how to do this please refer to [livereload.com/extensions/](http://livereload.com/extensions/).

Add, remove, modify file system patterns specified in the `depserve.options.livereload` array in your `Gruntfile.js`

This is an example depserve configuration:

```
depserve: {
    options: {
        open: '&lt;%= depserveOpenUrl %&gt;,
        livereload: [__dirname + "/js", __dirname + "/css", __dirname]
    }
}
```
### Extending behavior

See Polymer composition patterns

GE Coding Style Guide
---------------------

[GE JS Developer's Guide](https://github.com/GeneralElectric/javascript)


## Known Issues

Please use [Github Issues](https://github.com/PredixDev/px-datetime-field/issues) to submit any bugs you might find.
