Vanilla-JSX
=========

Vanilla-JSX is a library that converts JSX into vanilla HTML Elements.

#### Features

 - Converts JSX to vanilla HTMLElements
 - Translates className attribute into class
 - Supports arrays as children
 - Supports event listeners as attributes like `<div onClick={someFunction}></div>`

#### Example
```
'use babel'
/** @jsx vanilla.jsx */
import vanilla from 'vanilla-jsx'

console.log(
  <div class="Wow">Something <span>Special</span></div>
)
```

#### LICENSE
This project is licensed under the terms of MIT License, See the LICENSE file for more info
