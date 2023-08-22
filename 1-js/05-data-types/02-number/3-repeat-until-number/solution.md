
```js run demo
function repeatUntilNum() {
    let num = prompt("enter a number");
    return isNaN(num) ? repeatUntilNum() : num == 0 ? null : num;
}
repeatUntilNum();
```

The solution is a little bit more intricate that it could be because we need to handle `null`/empty lines.

