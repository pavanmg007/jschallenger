<div align="center">
  <img height="60" src="https://img.icons8.com/color/344/javascript.png">
  
   <a href="https://www.jschallenger.com/">https://www.jschallenger.com/</a>
  <h1>JS Challenger Solutions</h1>
</div>

##### 1. Write a function that takes an array (a) and a value (n) as argument Return the nth element of 'a'

<details><summary><b>Solution</b></summary>

```javascript
function myFunction(a, n) {
  return a[n - 1];
}
console.log(myFunction([1, 2, 3, 4, 5], 3));
```

</details>

##### 2. Write a function that takes two values, say a and b, as arguments. Return true if the two values are equal and of the same type

<details><summary><b>Solution</b></summary>

```javascript
function myFunction(a, b) {
    return a===b;
}
console.log(myFunction(2, 3));
```

</details>