Module JavaScript qui gère les nombres, les entiers, les doubles, les floats et biens d'autres sous types de nombre

## Installation

`npm install --save mbnumber`

instanciation du module

```js
var mbn = require("mbnumber");

```

#### isIntValid
Vérifie si la valeur passée en paramètre est réellement un entier valide
```js
let value = "34";

if (mbn.isIntValid(value)) {
    console.log("Correct");
}else {
    console.log("Invalid integer")
}
```