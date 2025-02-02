# Sticky

### Intro

When the component rolls out of screen range, it will always be fixed at the top of the screen.

### Install

```tsx
import "quarkd/lib/sticky";
```

### Basic Usage

```html
<quark-sticky offsettop="17vw">
  <div value="basic usage">Basic Usage</div>
</quark-sticky>
```

### Offset Top

```html
<quark-sticky offsettop="45vw">
  <div value="offset top">Offset Top</div>
</quark-sticky>
```

## API

### Props

| Attribute | Description         | Unit      | Default |
| --------- | ------------------- | --------- | ------- |
| offsettop | Offset top          | `vw `     | `0vw`   |
| zindex    | z-index when sticky | `number ` | `99`    |
