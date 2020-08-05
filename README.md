# Steps to reproduce

Run `npm install`  
Run `npm start`

Output:

```
node index.js

/Users/novar/repos/tmp/node_modules/uuid/dist/esm-browser/index.js:1
export { default as v1 } from './v1.js';
^^^^^^

SyntaxError: Unexpected token 'export'
    at wrapSafe (internal/modules/cjs/loader.js:1043:16)
    at Module._compile (internal/modules/cjs/loader.js:1091:27)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:1160:10)
    at Module.load (internal/modules/cjs/loader.js:976:32)
    at Function.Module._load (internal/modules/cjs/loader.js:884:14)
    at Module.require (internal/modules/cjs/loader.js:1016:19)
    at require (internal/modules/cjs/helpers.js:69:18)
    at Object.<anonymous> (/Users/novar/repos/tmp/index.js:1:24)
    at Module._compile (internal/modules/cjs/loader.js:1121:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:1160:10)
npm ERR! code ELIFECYCLE
npm ERR! errno 1
npm ERR! tmp@1.0.0 start: `node index.js`
npm ERR! Exit status 1
npm ERR!
npm ERR! Failed at the tmp@1.0.0 start script.
npm ERR! This is probably not a problem with npm. There is likely additional logging output above.

npm ERR! A complete log of this run can be found in:
```
