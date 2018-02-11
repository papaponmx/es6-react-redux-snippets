# es6-react-redux-snippets
This is the best package ever created for ES6, React and Redux


Here is a table with all available snippets.

**Note:** The _$1_ or _${1:params}_ is the position where the cursor will be when the snippet is triggered, if you see a following number, it means that you can press tab and cursor will move to that space.

Enjoy :D


## ES6+ Snippets

|Prefix|Method|
|-------:|-------|
|`log→`|`console.log(${1:msg})`|
|`anfn→`|`(${1:params}) => {  $2 }`|
|`nfn→`|`const ${1:functionName} = (${2:params}) => { $3 }`|
|`fn→`|`function ${1:functionName} (${2:params}) {  $3  }`|
|`imp→`|`import ${1:ModuleName} from '${2:Module}';`|
|`imd→`|`import { ${1:destructuredModule} } from '${2:module}'`|
|`ime→`|`import * as ${1:alias} from '${2:module}`|
|`fof→`|`for(let ${1:itemName} of ${2:iterable} { $3  }`|
|`fin→`|`for(let ${1:itemName} in ${2:iterable} { $3 }`|
|`met→`|`${1:methodName} = (${2:params}) => { $3 }`|
|`seto→`|`setTimeOut(($2) => { $3 }, ${1:timeOut});`|
|`npro→`|`new Promise((${1:resolve}, ${2:reject}) => )`|

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
