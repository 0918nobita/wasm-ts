# wasm-ts

TypeScript type definitions for [WebAssembly API](https://developer.mozilla.org/en-US/docs/WebAssembly)

## Installation

### npm

```bash
npm i -S wasm-ts
```

### yarn

```bash
yarn add wasm-ts
```

## Example

```typescript
import { WebAssembly } from 'wasm-ts';

WebAssembly.instantiateStreaming(fetch('example.wasm')).then(obj => {
  obj.instance.exports.func();
});
```

## Changelog

### [0.1.2] - 2019.05.06

- Add LICENSE
- Add README.md

### [0.1.0] - 2019.05.06

- Add ``index.d.ts`` (declaration file)
