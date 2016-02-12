### REST API を呼び出す

jQuery を使った場合...

```javascript
$.ajax({
  url: 'http://echo.jsontest.com/title/ipsum/content/blah',
  method: 'get'
})
  .then(function (data) {
    // data 変数に結果が入っているので
    // ここで加工して表示する
    console.log(data);
  })
  .fail(function (error) {
    // エラーがあった時はここ!
    console.log(error);
  });
```

* 今日は POST とかはやりません...
