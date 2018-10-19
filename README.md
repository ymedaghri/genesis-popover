# \<genesis-popover\>

This project is a polymer component that can be used to toggle/untoggle a popover on click.

[GitHub Repository](https://github.com/ymedaghri/genesis-popover.git)


## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```

```
$ polymer serve  --open
```

Open `localhost:8080/components/genesis-popover/demo/` in your browser. (Note that the path uses `genesis-popover`—the
component name listed in this element's `bower.json` file—rather than the actual directory name.)

## Running Tests

```
$ polymer test
```

```
$ polymer test -l chrome
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.

## WARNING

The vaadin flow-maven-plugin has a bug preventing the packaging of popper.js. (https://github.com/vaadin/flow/issues/4415).

We have brutally copied the popper.js minified file in the meantime.
