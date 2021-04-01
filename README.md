<p align="center">
    <img src="https://user-images.githubusercontent.com/6702424/80216211-00ef5280-863e-11ea-81de-59f3a3d4b8e4.png">  
</p>
<p align="center">
    <i></i>
    <br>
    <br>
    <img src="https://github.com/garronej/silver-broccoli/workflows/ci/badge.svg?branch=main">
    <img src="https://img.shields.io/bundlephobia/minzip/silver-broccoli">
    <img src="https://img.shields.io/npm/dw/silver-broccoli">
    <img src="https://img.shields.io/npm/l/silver-broccoli">
</p>
<p align="center">
  <a href="https://github.com/garronej/silver-broccoli">Home</a>
  -
  <a href="https://github.com/garronej/silver-broccoli">Documentation</a>
</p>

# Install / Import

```bash
$ npm install --save silver-broccoli
```

```typescript
import { myFunction, myObject } from "silver-broccoli";
```

Specific imports:

```typescript
import { myFunction } from "silver-broccoli/myFunction";
import { myObject } from "silver-broccoli/myObject";
```

## Import from HTML, with CDN

Import it via a bundle that creates a global ( wider browser support ):

```html
<script src="//unpkg.com/silver-broccoli/bundle.min.js"></script>
<script>
    const { myFunction, myObject } = silver_broccoli;
</script>
```

Or import it as an ES module:

```html
<script type="module">
    import { myFunction, myObject } from "//unpkg.com/silver-broccoli/zz_esm/index.js";
</script>
```

_You can specify the version you wish to import:_ [unpkg.com](https://unpkg.com)

## Contribute

```bash
npm install
npm run build
npm test
```
