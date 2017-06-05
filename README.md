# Utility class for silc framework

## Visibility
Hide and show elements, globally, or at specific breakpoints.

### Hide
```html
<div class="silc-hide">
    <p>Hidden at all screen sizes</p>
</div>
```

#### Modifiers
Elements can be hidden at speficic breakpoints using modifier classes in the `silc-hide--{breakpoint}` format e.g.
```html
<div class="silc-hide--small">
    ...
</div>
```

### Display
```html
<div class="silc-display">
    <p>Display block at all screen sizes</p>
</div>
```

#### Modifiers
Elements can be displayed at specific breakpoints using modifier classes in the `silc-display--{display-type}-{breakpoint}` format e.g.
```html
<div class="silc-display--inline-small">
    <p>Display inline at small screen sizes and above</p>
</div>
```
__Note:__ Current display types are:
 - block
 - inline
 - inline-block
 - flex
