# nested-includer
A web component that lets users add support for nested elements in their components

### Installation

```shell
bower install --save pancake-cms-nested-includer
```

### Usage

While creating your element, you will need to append the `NestedIncluderBehavior` to your code.

```javacript
Polymer({
    is: 'my-element',
    behaviors: [NestedIncluderBehavior]
});
```