# URL Differentiator

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://mashukealam.github.io)


It'll give you all the matched URL in a string. Great for parsing and making formatted anchor tags.

  
  - Built in 20 min 

# Installations
```npm i url_differentiator```

# Usage
Use the formulas by passing variables:
``` 
const {ifURL} = require('url_differentiator');
let matches = ifURL("this is a test string this is facebook.com and we also have https://google.com")
console.log(matches); // gives you Object [RegExp String Iterator] {}

for (const match of matches) {
  console.log(match); // the matched URL
  console.log(match.index) // index of that!
}
```

# Contacts
** My Email: mjim181145@bscse.uiu.ac.bd
** My FB: Mash Jim
** My Dept. & Roll: CSE - 011-181-145


:green_heart: :green_heart: :green_heart:
:purple_heart: :purple_heart: :purple_heart:
### Thanks