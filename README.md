# jhom
### writing lyrics using thesarus.

```
npm init
npm i thesaurus -S
```

```js
var tcom = require('thesaurus-com');
 
var sea1=tcom.search('constellation');
var syn=sea1.synonyms;

console.log(syn.length);

function getRan(min, max) {
return Math.floor(Math.random() * (max - min) + min);
}

var get=getRan(1,syn.length); 

console.log(get);
```
