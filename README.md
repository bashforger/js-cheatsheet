# js-cheatsheet


- Function to find occurance of a 'val' in an 'arr'

```javascript
const occurrences = (arr, val) => arr.reduce((a, v) => (v === val ? a + 1 : a), 0);
```
