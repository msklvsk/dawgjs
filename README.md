DAWG (directed acyclic word graph), also called DAFSA ([Wikipedia](https://en.wikipedia.org/wiki/Deterministic_acyclic_finite_state_automaton)) is a data structure that lets you efficiently store sets of strings and also provides prefix search.

**dawgjs** reads DAWG files created by [dawgdic](https://code.google.com/archive/p/dawgdic/) C++ library or [DAWG](https://github.com/kmike/DAWG) python package.

## Installation
```
npm install dawgjs
```

## Usage

### typescript
```ts
// todo
```

### es6
```js
// todo
```

## Real-world use-case
**dawgs** is used to pack an entire morphological dictionary of Ukrainian (~5 million interpretations) into < 4MB which allows to tag texts directly in the browser. See [https://experimental.mova.institute/apps/morph-analyzer](https://experimental.mova.institute/apps/morph-analyzer).

## Current limitations
- This package can't create DAWGs.
- Targeting ES6. Additional transpilation required if targeting ES5/ES3.

## Licence
[MIT](https://github.com/msklvsk/dawgjs/blob/master/LICENSE).

## Contribution
Questions, feature requests, ideas, bugs or PRs are always welcomed on [github](https://github.com/msklvsk/dawgjs/issues/new).

## Development
```bash
git clone https://github.com/msklvsk/dawgjs.git
cd dawgjs
npm install
npm run build:watch
```
