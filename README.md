<div align="center">
  <img height="60" src="https://img.icons8.com/color/344/javascript.png">
  
   <a href="https://www.jschallenger.com/">https://www.jschallenger.com/</a>
  <h1>JS Challenger Solutions</h1>
</div>

##### 1. Write a function that takes an array `(a)` and a value `(n)` as argument Return the `nth` element of `'a'`

```javascript
function myFunction(a, n) {
  //code
}
myFunction([1, 2, 3, 4, 5], 3);
```

<details><summary><b>Solution</b></summary>

```javascript
function myFunction(a, n) {
  return a[n - 1];
}
console.log(myFunction([1, 2, 3, 4, 5], 3));
```

</details>

---

##### 2. Write a function that takes two values, say `a` and `b`, as arguments. Return `true` if the two values are equal and of the same type

```javascript
function myFunction(a, b) {
  //code
}
myFunction(2, 3);
```

<details><summary><b>Solution</b></summary>

```javascript
function myFunction(a, b) {
  return a === b;
}
console.log(myFunction(2, 3));
```

</details>

---

##### 3. Write a function that takes an array `(a)` as argument. Return the `number` of elements in `a`

```javascript
function myFunction(a) {
  //code
}
myFunction([2, 3, 4, 5]);
```

<details><summary><b>Solution</b></summary>

```javascript
function myFunction(a) {
  return a.length;
}
console.log(myFunction([1, 2, 2, 4]));
```

</details>

---
##### 4. Write a function that a string `(a)` as argument Create an `object` that has a property with key `'key'` and a value of `(a)` Return the `object`

```javascript
function myFunction(a) {
  //code
}
myFunction('z');
```

<details><summary><b>Solution</b></summary>

```javascript
function myFunction(a) {
  return {key:a};
}
console.log(myFunction('z'));
```

</details>

---
##### 5. Write a function that takes a `string` as argument. Extract the `last 3` characters from the string. Return the `result`

```javascript
function myFunction(str) {
  //code
}
myFunction('string');
```

<details><summary><b>Solution</b></summary>

```javascript
function myFunction(str) {
  return str.slice(-3);
}
console.log(myFunction('string'));
```

</details>

---
##### 6. Write a function that takes a `string` `(a)` as argument. Extract the `first half` a. Return the `result`

```javascript
function myFunction(a) {
  //code
}
myFunction('string');
```

<details><summary><b>Solution</b></summary>

```javascript
function myFunction(a) {
  return a.slice(0, a.length/2);
}
console.log(myFunction('string'));
```

</details>

---
##### 7. Write a function that takes a string `(a)` as argument, Get the `first 3` characters of a Return the `result`

```javascript
function myFunction(a) {
  //code
}
myFunction('string');
```

<details><summary><b>Solution</b></summary>

```javascript
function myFunction(a) {
  return a.slice(0, 3);
}
console.log(myFunction('string'));
```

</details>

---
##### 8. Write a function that takes an array `(a)` as argument, Extract the `first 3` elements of a Return the resulting `array`

```javascript
function myFunction(a) {
  //code
}
myFunction([1,2,3,4,5]);
```

<details><summary><b>Solution</b></summary>

```javascript
function myFunction(a) {
  return a.slice(0, 3);
}
console.log(myFunction([1,2,3,4,5]));
```

</details>

---
##### 9. Write a function that takes `'a'` value as argument, Return the `type` of the value

```javascript
function myFunction(a) {
  //code
}
myFunction([1,2,3,4,5]);
```

<details><summary><b>Solution</b></summary>

```javascript
function myFunction(a) {
  return typeof a;
}
console.log(myFunction([1,2,3,4,5]));
```

</details>

---
##### 10. Write a function that takes an `array` of `strings` as argument, `Sort` the `array elements` `alphabetically`, Return the `result`

```javascript
function myFunction(arr) {
  //code
}
myFunction(['hello','world','learning','js','is','fun']);
```

<details><summary><b>Solution</b></summary>

```javascript
function myFunction(arr) {
  return arr.sort();
}
console.log(myFunction(['b','c','f','e','d','a']));
```

</details>

---
##### 11. Write a function that takes a string `(a)` and a number `(n)` as argument. Return the `nth` character of `'a'`

```javascript
function myFunction(a,n) {
  //code
}
myFunction('javascript', 5);
```

<details><summary><b>Solution</b></summary>

```javascript
function myFunction(a,n) {
  return a.charAt(n-1); //also a[n-1]
}
console.log(myFunction('javascript', 5));
```

</details>