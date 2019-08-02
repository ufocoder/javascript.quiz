JavaScript.Quiz
===============

Public issue collection of `What will be output?` that can be used for any javascript quiz or interview

Table of contents:

* [Operators issues](#operators-issues)
* [Scope issues](#scope-issues)
* [Prototype issues](#prototype-issues)


### Operators issues

1. 
```
console.log(-100 < 0 < 100);
console.log(-100 > 0 > 100);
```

2.
```
var number = 0;

console.log(number++);
console.log(++number);
console.log(number);
```

3.
```
var isJavaScriptSexist = '👧' < '👨';

console.log(isJavaScriptSexist)
```

4.

```
var trees = ["xyz", "xxxx", "test", "ryan", "apple"];

delete trees[3];

console.log(trees.length);
```

### Scope issues

1.
```
var foo = 'Hello';

(function() {
  var bar = ' World';
  console.log(foo + bar);
})();

console.log(foo + bar);
```

2.
```
myname = "global"; 

function func() { 
    console.log(myname); 
    var myname = "local"; 
    console.log(myname); 
} 

func(); 
```

## Prototype issues

1.
```
var Employee = {
  company: 'xyz'
}
var emp1 = Object.create(Employee);

delete emp1.company

console.log(emp1.company);
```

2.
```
var obj = {
    '0': 'a',
    '1': 'b',
    '2': 'c',
    'length': 3
}

obj.__proto__ = Array.prototype

console.log(...obj)
```
