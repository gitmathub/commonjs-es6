
If you run `npm run hello` then
the package.json and the line `"type": "module"` is essential.


Else you get an error: 
```shell
/Users/mat/Development/commonjs-es6/npm/world.js:1
import { out } from './baby.js'
^^^^^^

SyntaxError: Cannot use import statement outside a module
```