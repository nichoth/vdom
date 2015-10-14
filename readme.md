# vdom

Template for `virtual-dom` components.


## install

Clone this repo and add `vdom` to your path.


## use

    $ vdom make/this/Component.js

Will create a file like this:

```js
var h = require('virtual-dom/h');
var state = require('@nichoth/state');

module.exports = Component;

function Component(opts) {
  var s = state({
    
  });
  
  return s;    
}

Component.render = function(state) {
  return h('div', []);
};
```
