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




