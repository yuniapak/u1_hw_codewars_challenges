## Return Negative

```js
const makeNegative = (num) => {
  if (num <= 0) {
    console.log(num)
  } else {
    console.log(num * -1)
  }
}
makeNegative(1) // return -1
makeNegative(-5) // return -5
makeNegative(0) // return 0
makeNegative(0.12) // return -0.12
```

## Sum of Positive

```js
//Example [1,-4,7,12] => 1 + 7 + 12 = 20
//Note: if there is nothing to sum, the sum is default to 0.
const sumOfAnArray = (num) => {
  let sum = 0
  if (num === []) {
    console.log(0)
  } else {
    for (let i = 0; i < num.length; i++) {
      if (num[i] >= 0) {
        sum = sum + num[i]
      } else {
      }
    }
    console.log(sum)
  }
}
sumOfAnArray([1, -1, 5])
```

## Function 2

```js
//Now you have to write a function that takes an argument and returns the square of it.

const squareFunction = (num) => {
  console.log(num * num)
}

squareFunction(2) //4
```

## Sum Arrays

```js
const sumOfAnArray = (num) => {
  let sum = 0
  if (num === []) {
    console.log(0)
  } else {
    for (let i = 0; i < num.length; i++) {
      sum = sum + num[i]
    }
    console.log(sum)
  }
}

sumOfAnArray([1, 5.2, 4, 0, -1]) //9.2
sumOfAnArray([]) //0
sumOfAnArray([-2.398]) //-2.398
```

## Reversed Strings

```js
const reversString = (string) => {
  let newString = ''
  for (let i = string.length - 1; i >= 0; i--) {
    newString += string[i]
  }
  console.log(newString)
}
reversString('world') //dlrow
reversString('word') //drow
```
