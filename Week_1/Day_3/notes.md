# Objects

### key points
- using function expression (ie const name = function...) prevents hoisting
- as opposed to (function name ()....) which ALLOWS hoisting
- special case "var" : declaration (creating the variable) and initialization (setting the value) occur at different times;

- use key notation when property name is known

- use square bracket notation when property name is unknown, undeclared or assigned to variable;

- objects can be looped through via properties using 
```
for (let properties in object) {
  ie objects.properties....
}