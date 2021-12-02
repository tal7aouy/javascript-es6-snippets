# JavaScript && Typescript

## VS Code JavaScript (ES6+) snippets

---

This extension contains code snippets for JavaScript in ES6 syntax for [Vs Code][code] editor (supports both JavaScript and TypeScript).

## Installation

1. Open the extensions sidebar on Visual Studio Code
1. Search for Javascript(ES6)
1. Click Install
1. 🌟🌟🌟🌟🌟 Rate five-stars 😃

## The languages supported (file extensions)

- JavaScript (.js)
- TypeScript (.ts)
- JavaScript React (.jsx)
- TypeScript React (.tsx)
- Html (.html)
- Vue (.vue)

## Snippets

Snippets are optimized to be short and easy to remember.

Below is a list of all available snippets and the triggers of each one. The ⇥ means the TAB key.

### Import and export

| Trigger | Content                                                                                                |
| ------: | ------------------------------------------------------------------------------------------------------ |
|  `imp⇥` | imports entire module `import fs from 'fs';`                                                           |
|  `imn⇥` | imports entire module without module name `import 'bootstrap.min.css'`                                 |
|  `imd⇥` | imports only a portion of the module using destructing `import {rename} from 'fs';`                    |
|  `ime⇥` | imports everything as alias from the module `import * as alias from 'fs';`                             |
|  `ima⇥` | imports only a portion of the module as alias `import { rename as localRename } from 'fs';`            |
|  `rqr⇥` | require package `require('');`                                                                         |
|  `req⇥` | require package to const `const packageName = require('packageName');`                                 |
|  `mde⇥` | default module.exports `module.exports = {};`                                                          |
|  `env⇥` | exports name variable `export const nameVariable = localVariable;`                                     |
|  `enf⇥` | exports name function `export const log = (parameter) => { console.log(parameter);};`                  |
|  `edf⇥` | exports default function `export default function fileName (parameter){ console.log(parameter);};`     |
|  `ecl⇥` | exports default class `export default class Calculator { };`                                           |
|  `ece⇥` | exports default class by extending a base one `export default class Calculator extends BaseClass { };` |

### Object and Class helpers

|  Trigger | Content                                                                                             |
| -------: | --------------------------------------------------------------------------------------------------- |
|   `con⇥` | adds default constructor in the class `constructor() {}`                                            |
|   `met⇥` | creates a method inside a class `test() {}`                                                         |
|   `pge⇥` | creates a getter property `get propertyName() {return value;}`                                      |
|   `pse⇥` | creates a setter property `set propertyName(value) {}`                                              |
|    `gs⇥` | creates a getter and setter property `set propertyName(value) {} get propertyName(){return value;}` |
|    `ol⇥` | creates an object literal `set propertyName(value) {}`                                              |
| `proto⇥` | creates a prototype method `obj.prototype.add = function() {}`                                      |
|    `oa⇥` | creates an object assign `obj.assign(destObj, sourceObj)`                                           |

### Various methods

|  Trigger | Content                                                                               |
| -------: | ------------------------------------------------------------------------------------- |
|   `fre⇥` | forEach loop in ES6 syntax `array.forEach(currentItem => {})`                         |
|   `fof⇥` | for ... of loop `for(const item of object) {}`                                        |
|   `fin⇥` | for ... in loop `for(const item in object) {}`                                        |
|  `anfn⇥` | creates an anonymous function `(params) => {}`                                        |
|   `nfn⇥` | creates a named function `const add = (params) => {}`                                 |
|    `gn⇥` | creates a generator `function* () {}`                                                 |
|   `gfn⇥` | creates a named generator `function* generator() {}`                                  |
|   `dob⇥` | destructing object syntax `const {rename} = fs`                                       |
|   `dar⇥` | destructing array syntax `const [first, second] = [1,2]`                              |
|   `sti⇥` | set interval helper method `setInterval(() => {});`                                   |
|   `sto⇥` | set timeout helper method `setTimeout(() => {});`                                     |
|  `prom⇥` | creates a new Promise `return new Promise((resolve, reject) => {});`                  |
| `thenc⇥` | adds then and catch declaration to a promise `.then((res) => {}).catch((err) => {});` |

### Console methods

| Trigger | Content                                                            |
| ------: | ------------------------------------------------------------------ |
|  `cas⇥` | console alert method `console.assert(expression, object)`          |
|   `cc⇥` | console clear `console.clear()`                                    |
|  `cco⇥` | console count `console.count(label)`                               |
|  `cdb⇥` | console debug `console.debug(object)`                              |
|  `cdi⇥` | console dir `console.dir`                                          |
|  `cer⇥` | console error `console.error(object)`                              |
|  `cgr⇥` | console group `console.group(label)`                               |
|  `cge⇥` | console groupEnd `console.groupEnd()`                              |
|   `cl⇥` | console log `console.log(object)`                                  |
|  `clo⇥` | console log object with name `console.log('object :>> ', object);` |
|  `ctr⇥` | console trace `console.trace(object)`                              |
|   `cw⇥` | console warn `console.warn`                                        |
|   `ci⇥` | console info `console.info`                                        |
|   `ct⇥` | console table `console.table`                                      |
|  `cti⇥` | console time `console.time`                                        |
|  `cte⇥` | console timeEnd `console.timeEnd`                                  |

### Timers & strict mode

| Trigger | Content                                |
| ------: | -------------------------------------- |
|  `sti⇥` | setInterval `setInterval(()=>{},time)` |
|  `sto⇥` | setTimeOut `setTimeOut(()=>{},time)`   |

### Types

| Trigger | Content                                           |
| ------: | ------------------------------------------------- |
|  `tof⇥` | typeof object or instance `typeof x === 'number'` |
|  `iof⇥` | instanceof `person instanceof Client`             |

### Miscellaneous

| Trigger | Content                         |
| ------: | ------------------------------- |
|   `us⇥` | use strict mode `'use strict';` |

### Testing (Mocha, Jasmine, etc.)

| Trigger | Content                                    |
| ------: | ------------------------------------------ |
| `desc⇥` | describe `describe('description',()=> {})` |
| `cont⇥` | context `context('description',()=> {})`   |
|   `it⇥` | it `it('description',()=> {})`             |
|  `its⇥` | it synchronous `it('description',()=> {})` |
|   `bf⇥` | before test suite `before(()=> {})`        |
|  `bfe⇥` | before each test `beforeEach(()=> {})`     |
|  `aft⇥` | after test suite `after(()=> {})`          |
|  `afe⇥` | after each test `afterEach(()=> {})`       |

### DOM

|    Trigger | Content                                       |
| ---------: | --------------------------------------------- |
|   `docId⇥` | `document.getElementById(selector);`          |
|    `docS⇥` | `"document.querySelector(selector);`          |
| `docSAll⇥` | `"document.querySelectorAll(selector);`       |
|    `docC⇥` | `"document.getElementsByClassName(selector);` |
|    `docC⇥` | `"document.getElementsByClassName(selector);` |
|    `dicN⇥` | `"document.getElementsByName(selector);`      |
|    `docT⇥` | `"document.getElementsByTagName(elem);`       |
|  `docTxt⇥` | `"document.createTextNode(text);`             |
|   `addEv⇥` | `"exmaple.addEventListener(event,()=>{});`    |

### Globals

|  Trigger | Content       |
| -------: | ------------- |
|  `desc⇥` | describe      |
| `desco⇥` | describe.only |
| `descs⇥` | describe.skip |
| `desce⇥` | describe.each |
|    `ae⇥` | after each    |
|    `aa⇥` | after all     |
|    `be⇥` | before each   |
|    `ba⇥` | before all    |

### Tests

|   Trigger | Content              |
| --------: | -------------------- |
|     `it⇥` | it                   |
|    `ito⇥` | it.only              |
|    `its⇥` | it.skip              |
|    `itt⇥` | it.todo              |
|    `ite⇥` | it.each              |
|    `ita⇥` | it(..., async ...)   |
|   `test⇥` | test                 |
|  `testo⇥` | test.only            |
|  `tests⇥` | test.skip            |
|  `testt⇥` | test.todo            |
|  `teste⇥` | test.each            |
| `testet⇥` | test.each (table)    |
|  `testa⇥` | test(..., async ...) |

### Expect

|   Trigger | Content                            |
| --------: | ---------------------------------- |
|    `exp⇥` | expect                             |
|   `expr⇥` | expect.resolves                    |
|  `exprj⇥` | expect.rejects                     |
|  `expas⇥` | expect.assertions(count)           |
|  `expha⇥` | expect.hasAssertions()             |
|     `tb⇥` | toBe                               |
|   `tbct⇥` | toBeCloseTo                        |
|    `tbd⇥` | toBeDefined                        |
|    `tbf⇥` | toBeFalsy                          |
|   `tbgt⇥` | toBeGreaterThan                    |
|  `tbgte⇥` | toBeGreaterThanOrEqual             |
|    `tbi⇥` | toBeInstanceOf                     |
|   `tblt⇥` | toBeLessThan                       |
|  `tblte⇥` | toBeLessThanOrEqual                |
|    `tbn⇥` | toBeNull                           |
|    `tbt⇥` | toBeTruthy                         |
|    `tbu⇥` | toBeUndefined                      |
|     `tc⇥` | toContain                          |
|    `tce⇥` | toContainEqual                     |
|     `te⇥` | toEqual                            |
|    `tse⇥` | toStrictEqual                      |
|   `thbc⇥` | toHaveBeenCalled                   |
|  `thbct⇥` | toHaveBeenCalledTimes              |
|  `thbcw⇥` | toHaveBeenCalledWith               |
| `thblcw⇥` | toHaveBeenLastCalledWith           |
|    `thl⇥` | toHaveLength                       |
|    `thp⇥` | toHaveProperty                     |
|     `tm⇥` | toMatch                            |
|    `tmo⇥` | toMatchObject                      |
|    `tms⇥` | toMatchSnapshot                    |
|   `tmis⇥` | toMatchInlineSnapshot              |
|     `tt⇥` | toThrow                            |
|    `tte⇥` | toThrowError                       |
|  `ttems⇥` | toThrowErrorMatchingSnapshot       |
| `ttemis⇥` | toThrowErrorMatchingInlineSnapshot |

### Templates

| Trigger | Content                 |
| ------: | ----------------------- |
|  `cut⇥` | test a class under test |
|  `jfn⇥` | jest.fn                 |

## Issues & Suggestions

For any issues or suggestions, please use [GitHub issues](https://github.com/tal7aouy/javascript-es6-snippets/issues).
