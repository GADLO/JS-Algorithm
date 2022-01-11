### 将摄氏度转换为华氏度

将摄氏度转换为华氏度的计算方式为：摄氏度乘以 `9/5` 然后加上 `32`。

```js
function convertToF(celsius) {
  let fahrenheit;
  return fahrenheit;
}

convertToF(30);
```

### 反转字符串

```js
function reverseString(str) {
  return str
    .split("")
    .reverse()
    .join("");
}
```

### 整数阶乘

```js
function factorialize(num) {
  if (num === 0) {
    return 1;
  }
  return num * factorialize(num - 1);
}

factorialize(5);
```

### 找出字符串中的最长单词

```js
function findLongestWordLength(str) {
  return Math.max(...str.split(" ").map(word => word.length));
}
```

