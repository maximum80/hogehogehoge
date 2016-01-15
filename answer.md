## タイトル：エンジニアに特化したポートフォリオアプリ

### 作品の説明
エンジニアの学生のために必要な情報を登録することが出来るポートフォリオアプリです。

### オリジナルで開発した機能
オリジナルで開発をしたのは、タグ機能です。
ユーザが、それぞれの技術に対するタグを登録することが出来る、訪問者がそれに対して評価ができるようにしました。

### 工夫した点

この辺。
```js:Hello.js
var assert = require("chai").assert;
var hello  = require("../app/hello.js");
describe("helloWorld", function() {
  it("Hello World!", function() {
    assert.equal(hello("World"), "Hello World!");
  });
  it("Hello codecheck!", function() {
    assert.equal(hello("codecheck"), "Hello codecheck!");
  });
});

```

### 利用した技術
- Node.js
- Express
- Bootstrap
- ReactJS
- gulp

### その他
