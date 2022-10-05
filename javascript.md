# Javascript 

### Let, Var & Const
|LET   |VAR   |   
|---|---|
|After 2015  |Before 2015   |
|Cannot be redeclared  |Can be redeclared   |   
|Block scope   |Global scope   |  
|Cannot be used without initialization| Initailization can be done later |


**Const** isused to make a permanent *reference* to an address space. Which means it cannot do the following  :
- Reassign constant value, array or object (cannot redeclare the entire thing)

But you can : 
- Change elements of the array (edit each element, add items)
- Change properties of object

***HOISTING***

'Var' elements are hoisted at the top. Which means you can use them anywhere in the program and initialize later. 
If this is done with 'const' or 'let', it will result in a reference error. This below statement is allowed.

```
x = 20;
var x;
```

### Events 

|Event |	Description|
|---|---|
|onchange |	An HTML element has been changed |
|onclick |	The user clicks an HTML element|
|onmouseover |	The user moves the mouse over an HTML element |
|onmouseout	|The user moves the mouse away from an HTML element |
|onkeydown|	The user pushes a keyboard key |
|onload	|The browser has finished loading the page |


### Strings

Strings can also be declared as objects. For example : 

```
let name = new String ("Isha");
```

However, this is not advised since javascript objects can never be compared to one another. I won't be able tof do this : 

```
let name = new String ("Isha");
let callMe = new String ("Isha");
return (name == callMe);
return (name === callMe);
```

Output will be false. 
