[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/bahrus/carbon-copy)

# \<genesis-popover\>

The genesis popover is a polymer element that can wrap any other DOM element and display a popover over it.
The popover can be displayed on the top, bottom, right, left, bottom-end .... of the wrapped element.

This webcomponent uses the library [Popper JS](https://popper.js.org) for positionning the popover depending on the wrapped element.

[GitHub Repository](https://github.com/ymedaghri/genesis-popover.git)


## Basic Example

```html
<genesis-popover placement="top">
  <input type="button" value="Pop Me with popper" />          <!-- Wrapped element -->
  <div slot="content">Adrienne is Rocky's soul mate</div>     <!-- Popover Content -->
</genesis-popover>
```

See More example in the polymer demo of this component.

## Window and Keyboard Events

The closing of the popover can be done either by : 
* Clicking again on the wrapped element
* Pressing Escape Key
* Clicking on the window outside of the popover content

## Theming

This component uses by default the [Vaadin Lumo Style Webcomponent](https://www.webcomponents.org/element/vaadin/vaadin-lumo-styles)

## Usage

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

```
$ polymer serve  --open
```

## Running Tests

```
$ polymer test
```

```
$ polymer test -l chrome
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
