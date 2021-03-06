importance: 5

---

# 新しい Accumulator を作る

コンストラクタ関数 `Accumulator(startingValue)` を作りなさい。

作成するオブジェクトは:

- "現在の値" をプロパティ `value` に格納します。開始値はコンストラクタ `startingValue` の引数がセットされます。
- `read()` メソッドは `prompt` を使って新しい値を読み込み、`value` に加算します。

つまり、`value` プロパティーはユーザーが入力したすべての値と初期値 `startingValue` の合計です。

これはそのコードのデモです:

```js
let accumulator = new Accumulator(1); // 初期値 1
accumulator.read(); // ユーザの入力値の加算
accumulator.read(); // ユーザの入力値の加算
alert(accumulator.value); // それらの値の合計を表示
```

[demo]
