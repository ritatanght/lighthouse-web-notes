# Scoping

When a local variable and a global variable have the same name, the local variable takes precedence within its scope.

```javascript
let myVar = "global";

const myFunction = function() {
  let myVar = "local";

  console.log("inside myFunction, myVar is:", myVar); 
}

myFunction();

console.log("outside myFunction, myVar is:", myVar);  
```

Output:
```{r}
inside myFunction, myVar is: local
outside myFunction, myVar is: global
```