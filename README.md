# es6-react-redux-snippets
This is the best package ever created for ES6, React and Redux


Here is a table with all available snippets.

**Note:** The _$1_ or _${1:params}_ is the position where the cursor will be when the snippet is triggered, if you see a following number, it means that you can press tab and cursor will move to that space.

Enjoy :D


## ES6+ Snippets


**log → console.log()**
![log snippet animation](./docs/log.gif)

**anfn → annonymous function**
![annonymous function snippet](./docs/anfn.gif)

**nfn→ named function**
![named function snippet](./docs/nfn.gif)

**fn → ES5 fucntion**
![ES5 function snippet](./docs/fn.gif)

**imp → import statement**
![import statement snippet](./docs/imp.gif)

**imd → import statement desctructured**
![import statement with destructuring snippet](./docs/imd.gif)

**ime→ import everything as**
![import everything snippet](./docs/ime.gif)

**fof→ for of loop**
![for of loop snippet](./docs/fof.gif)


|`fin→`|`for(let ${1:itemName} in ${2:iterable} { $3 }`|
|`met→`|`${1:methodName} = (${2:params}) => { $3 }`|
|`seto→`|`setTimeOut(($2) => { $3 }, ${1:timeOut});`|
|`npro→`|`new Promise((${1:resolve}, ${2:reject}) => )`|
|`catch→`|`catch() with nested annonymous function`|
|`then→`|`then() with nested annonymous function`|

## React

|Prefix|Method|
|-------:|-------|
|`rcc→`|`import React, { Component } from 'react';` <br> `export default class ${1:componentName}` <br> `extends Component {` <br> `render () {` <br> `return (` <br> `<div>` <br> `    $2` <br> `</div>` <br> `)` <br> `}` <br> `}`|
|`cpwm→`| `componentWillMount($1) { $2 }`|
|`rcredux→`| `Renders a React connected component`|




## React Redux

|Prefix|Method|
|-------:|-------|
|`rcredux→`|`React component with Redux`|
|`mapSta→`|`mapStateToProps function`|
|`mapDis→`|`mapDispatchToProps constant`|


#Redux

|Prefix|Method|
|-------:|-------|
|`rxconst→`|`export const ${1:constName} = '${1:constName}';`|
|`rxaction→`|`export const ${1:actionName} = ({2:param}) => ({` <br> `type: ${3:type}` <br> `payload: ${4:payload}` <br> `})`|
|`rxreducer→`|`Redux reducer template`|
