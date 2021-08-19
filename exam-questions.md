<!--? question 44 -->
In a Node.js program, what is the name of the global object used to access the current version of Node as well as arguments passed in from the command line: 
__

<!--* replacement suggestions -->
Node.js runs on the ___ answer: server

Node.js is ___ by default. answer: asynchronous





<!--? question 1 -->
Given the following code, what will be logged out to the console:
<pre><code>
var i = 10; 
for(var i = 1; i < 2; i++) {
  console.log("i");
}
console.log(i);</code>
</pre>

<!--* replacement suggestions -->
Which React Hook would you use to add state to a function component? answer: useState (wrong: createState, stateHook, useEffect)





<!--? question 20 -->
What value will the variable result contain, given the following?<pre><code>var ingredients = ['eggs','toast','orange juice'];
function cook(ingredients) {
  ingredients[0] = 'bread';
  ingredients[1] = 'cheese';
  ingredients[2] = 'pickle';
}
var result = cook(ingredients);</code>
</pre>

<!--* replacement suggestion -->
Two paragraph elements inside the same div element are considered answer: siblings (wrong: cousins, relatives, neighbors)





<!--? question 32 -->
What is the value of <code>this</code> inside a function that has been called with the <code>new</code> keyword?

<!--* replacement suggestion -->
Which of the following snippets of code will return `undefined`?

let x = this;

"use strict";
let x = this;

function myFunction() {
  return this;
}

<!-- correct -->
"use strict";
function myFunction() {
  return this;
}





<!--? question 41 -->
What line can we add to the end of this code to set up <code>Dog</code>'s prototype to inherit from <code>Animal?</code><pre><code>function Animal(type) {
  this.type = type;
}
Animal.prototype.getType = function() {
  return this.type;
}
function Dog() {
  var type = 'dog';
  Animal.call(this, type);
}</code>
</pre>
​
<!--* replacement suggestions -->
How would you set the value of state for `isLoading` to `true` in a React Class component?
​
<!-- correct -->
<code>this.setState({isLoading: true})</code>
<!-- wrong -->
<code>this.state.isLoading = true</code>
<code>this.state(isLoading = true)</code>
<code>this.setState.isLoading = true})</code>
​
​


​
<!--? question 19 -->
Given the following Node.js snippet, and assuming <code>func1</code> and <code>func2</code> are functions which have been previously defined, which function will execute first, <code>func1</code> or <code>func2</code>?<pre><code>
const fs = require('fs');
fs.open('./file.js','w',func1);
func2();</code>
</pre>
​
<!--* replacement suggestions -->
Node.js is the most widely used ____ environment for backend or server side JavaScript.
​
<!-- correct -->
<code>runtime</code>
<!-- wrong -->
<code>global</code>
<code>browser</code>
<code>built-in</code>
​
​
​
​
​
<!--? question 28 -->
In a Node.js program, which event gets triggered when information is being read from a stream, like an HTTP request?
​
<!--TODO replacement suggestion -->
​
​
​
​
​
​
<!--? question 14 -->
Given the following code, how would you dynamically access the value of the prop key in the obj object?<pre><code>var p = 'prop';
var obj = { prop: 'value' };</code>
</pre>
​
<!--* replacement suggestion -->
Given the following code, how would you dynamically access the value of the prop key in the obj object?
```js
const p = 'prop';
const obj = { prop: 'value' };
```
​
<!-- correct -->
<code>obj[p]</code>
