# javascript-objects-and-prototypes

# plnk.co
`http://plnkr.co/edit/J81EK3TWFof0ekhEnyiJ?p=preview`
forked
`http://plnkr.co/edit/XAI4tl7XlJgHvyq3e2yb?p=preview`

# display.js
`display.js` has a display() function is very useful.

**Example** `display('Hello World')`

## script.js
`'use strict';`
Strict mode causes JavaScript to throw erros in places it would, otherwise, just silently fail.
Using strict mode disallows the use of deprecated parts of JavaScript.

### The Object Literal
Define the properties and their values inside braces.

`var dog = {
  name: 'Fluffy',    
  color: 'Red' 
}`

### Utilizing the Object Literal
`'use strict'`

`var dog = { name: 'Fluffy', color: 'Red' }`

`display(dog.name);`

### Modifying the Object Literal on the fly
`'use strict'`

`var dog = { name: 'Fluffy', color: 'Red' }`

`dog.age = 3`

`display(dog.age)`

### Functions as Property Values
`'use strict'`

`var dog = { name: 'Fluffy', color: 'Red' }`

`dog.speak = function() { display("bork!") }`

`dog.speak()`

### The new keyword 
`'use strict'`

`function Cat() {
  this.name = 'Fluffy'
  this.color = 'White'
}`

`var cat = new Cat();`

`display(cat);`

**NOTE:** Be mindful of the this keyword!
