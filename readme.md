# mjs-commonjs-default

demo that shows difference in module resolution for `js` and `mjs` files.

## how to run

```bash
mjs-commonjs-default % node src/index.mjs
{ default: 42 }
mjs-commonjs-default % node dist/mjs.js  
{ default: 42 }
mjs-commonjs-default % node dist/js.js
42
mjs-commonjs-default % node src/index.js 
{ default: 42 }
```