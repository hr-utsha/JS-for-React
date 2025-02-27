<h2>Calculator.js </h2>

```
let sum = (a,b)=>{
    return a + b ;
}
let sub = (a,b)=>{
    return a - b ;
}

let mul = (a,b)=>{
    return a * b ;
}

export {sum,sub,mul}
```


<h2>index.js</h2>

```
import {sum,sub, mul as m} from "./Calculator.js"

console.log(sum(30,20));
console.log(sub(40,20));
console.log(m(40,20));
```

