# sur.org
a hub of indigenous knowledge and wisdom

<details>
<summary>🥚 inner and outer scope</summary>

```js
console.log('-- block scope: inner and outer scope --');

let outerVariable = 'declared outside';
console.log(outerVariable); // 'declared outside'

// begin a new block scope
{
  // variables declared outside of curly are available inside the curly braces
  outerVariable = 'assigned inside';
  console.log(outerVariable); // 'assigned inside'

  let innerVariable = 'declared inside';
  console.log(innerVariable); // 'declared inside'
}

// changes made inside the scope stay when you leave the scope
console.log(outerVariable); // 'assigned inside'

// variables declared in the inner scope are NOT available outside
console.log(innerVariable); // ReferenceError
```

</details>
<detailes>
<summary>Extend the below arrow</summary>
```js
/* Here I am hidinng some text just to check how it is going to appear later on.
Here I am hidinng some text just to check how it is going to appear later on.
Here I am hidinng some text just to check how it is going to appear later on.
Here I am hidinng some text just to check how it is going to appear later on.
Here I am hidinng some text just to check how it is going to appear later on.
Here I am hidinng some text just to check how it is going to appear later on.
Here I am hidinng some text just to check how it is going to appear later on.
Here I am hidinng some text just to check how it is going to appear later on.
Here I am hidinng some text just to check how it is going to appear later on.
Here I am hidinng some text just to check how it is going to appear later on.
Here I am hidinng some text just to check how it is going to appear later on.
Here I am hidinng some text just to check how it is going to appear later on.
Here I am hidinng some text just to check how it is going to appear later on.
Here I am hidinng some text just to check how it is going to appear later on.
Here I am hidinng some text just to check how it is going to appear later on.*/
```
</details>
