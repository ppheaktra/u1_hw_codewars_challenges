## Return Negative

```js
function makeNegative(num) {
  return num > 0 ? -num : num
}
```

## Sum of Positive

```js
function positiveSum(arr) {
  let sum = 0;
  arr.forEach(function(e{
    if (e>=0) sum += e
  })
  return sum;
}
```
## Function 2

```js
function square (number){
return number * number
}
```

## Sum Arrays

```js
function total(arr) {
  if(!Array.isArray(arr)) return;
  let total = 0;
  for (let i=0,l=arr.length; i<l; i++) {
     total+=arr[i];
  }
  return total;
}
//https://stackoverflow.com/questions/1230233/how-to-find-the-sum-of-an-array-of-numbers
```

## Reversed Strings

```js
function solution(str){
  let x = ''
  for(let i of str){
    x = i+x
  }
  return x
}
```
