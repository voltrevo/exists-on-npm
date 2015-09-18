# exists-on-npm

Create a promise for whether an npm module exists

``` bash
npm install --save exists-on-npm
```

``` javascript
'use strict';

var existsOnNpm = require('exists-on-npm');

existsOnNpm('zealous-octo-succotash').then(function(exists) {
  console.log(exists); // false (at time of writing)
});
```
