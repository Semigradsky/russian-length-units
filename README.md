# Russian length units

## Install
```
npm install russian-length-units
```

## Usage
```js
import units from 'russian-length-units';
import random from 'random-int';

console.log(units[random(units.length - 1)]);

// => {
//       "names": ["perst", "persta", ..., "перст", ...], // names
//       "value": 0.02                                    // value in meters
//    }
```

