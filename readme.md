## 1. What is the difference between var, let, and const?

`var` has **function scope** but `let` and `const` have **block scope**.

`var`, we can declare a variable and change its value later.  
`let`, we can also change the value but we cannot redeclare it in the same scope. In addition, it is the modern and more reliable version of var 
`const`, the value cannot be changed after declaration.

`var` variables are hoisted but their value becomes **undefined** before initialization.  
`let` variables are also hoisted but if we try to access them before declaration it gives an **error**.  
`const` works similar to `let`. But we can not change the value.


