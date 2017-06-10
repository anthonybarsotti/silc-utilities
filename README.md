# silc utilites [![npm version](https://badge.fury.io/js/silc-utilities.svg)](https://badge.fury.io/js/silc-utilities)
The utilities module is a small web component for the [silc framework](https://silc.io).

## Display
Display elements, globally, or at specific breakpoints.

```html
<div class="silc-display">
    <p>Display block at all screen sizes</p>
</div>
```

### Modifiers
Elements can be displayed at specific breakpoints using modifier classes in the `silc-display--{display-type}-{breakpoint}` format e.g.
```html
<div class="silc-display--none">
    <p>Display none at all screen sizes</p>
</div>
<div class="silc-display--inline-small">
    <p>Display inline at small screen sizes and above</p>
</div>
```

### Variables
Display types can be configured via the `$silc-utilities--display-types` variable. By default, the following display types are available:

```scss
$silc-utilities--display-types: (
    'block',
    'inline',
    'inline-block',
    'flex',
    'none'
) !default;
```
