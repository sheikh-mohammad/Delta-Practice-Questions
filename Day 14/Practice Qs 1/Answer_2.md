```js
let hindi = 80;
let eng = 90;
let math = 100;
let avg = (hindi + eng + math) / 3;
```

## My Solution

1. In the first line we declare and initialize the variable `hindi` with value `80`.
2. In the second line we declare and initialize the variable `eng` with value `90`.
3. In the third line we declare and initialize the variable `math` with value `100`.
4. In the fourth line we declare and initialize the variable `avg` with value `(hindi + eng + math) / 3`.
5. But the fourth line will execute different, since javascript has specific operator precedence, and according to operator precendence first `()` then `**` (right to left) then `/ and *` (left to right) then `+ and -` (left to right).
6. SO now first brackets will be exceute and in it we have `(hindi + eng + math)` which results `270`.
7. Now brakcets have been solved and at last we have division so divide the `270` with `3` so it will be `90`.