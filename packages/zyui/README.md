# @zytechg/zyui v1.2.0

ZyUI is the shared UI framework for ZyFOCUS and the wider ZyTech package ecosystem. It combines a polished CSS system with the ZyJS runtime and optional components for fast, consistent interfaces.

## What ships

- `zy-ui.css` for the framework stylesheet
- `zyjs.js` for the ZyJS runtime
- `zyjs.components.js` for optional `data-zyjs` behaviors
- `docs/` for the docs hub, demo, and changelog snapshots

## Install

```bash
npm install @zytechg/zyui
```

## Quick Start

### CSS

```html
<link rel="stylesheet" href="node_modules/@zytechg/zyui/zy-ui.css">
```

### JS

```html
<script src="node_modules/@zytechg/zyui/zyjs.js"></script>
<script src="node_modules/@zytechg/zyui/zyjs.components.js"></script>
```

### Module import

```js
import '@zytechg/zyui/zyjs.js';
import '@zytechg/zyui/zyjs.components.js';
```

## Real Demo

The package includes a real static demo and docs hub:

- `docs/index.html`
- `docs/demo.html`

The demo shows:

- the package layout
- a copy-to-clipboard interaction
- an active-state toggle
- the package shell and card rhythm

## Package Layout

- `docs/` for docs and demo pages
- `zy-ui.css` for styles
- `zyjs.js` for the runtime
- `zyjs.components.js` for optional components
- `README.md` for package overview
- `CHANGELOG.md` for release history

## Notes

1. ZyUI is additive: apply it alongside your app classes.
2. ZyJS components auto-mount on `[data-zyjs]` elements.
3. The package is designed to feel production-ready from the first install.
