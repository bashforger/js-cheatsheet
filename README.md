# js-cheatsheet


- **Function to find number of occurances of 'val' in an 'arr'**

```javascript
const occurrences = (arr, val) => arr.reduce((a, v) => (v === val ? a + 1 : a), 0);
```




- **Function to find and replace array element 'a' with 'b' in position.**

```javascript
array = array.map(function(item) { return item == 'a' ? 'b' : item; });;
```
**OR**

```javascript
array.forEach(function(item, i) { if (item == 'a') a[i] = 'b'; });
```




- **Function to find unique values in an Array**

```javascript
const uniqueArrayElements = arr.filter((value, index, self) => self.indexOf(value) == index)
```
