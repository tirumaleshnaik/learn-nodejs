global is the global object in the node.js


globalThis is a global object who ever follows ecma script standards



Including modulescls

Modules are protected by default

need to do export and import to access the variables and function inside the file

Common js modules(cjs) - by default it will be enabled
module.exports -  export
require - import

es modules (mjs)
import fs from 'fs' - import
export - export

both have theire pros and cons

suggested is to use - es module
reasons
1. It is now used heavily and ecma is promoting more
2. it is the future
3. Syntax is supported in the browsers also
4. Both static and dynamic imports are possible
5. Newer way
6. It is becoming the standard going forward
7. code runs in strict mode



require("./path)
1. resolving the module
2. loading the module
3. wraps inside a iife
4. evaluation 
5. caching if multiple files needs same module

Node.js

nodejs has event driven architecture and asynchronous

