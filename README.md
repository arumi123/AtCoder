# AtCoder
At Coderで学んだことをここへ記載していく

## split関数
- 文字列型変数に対して、有効なメソッド
- 指定された区切り文字で分割し、リストとして返すメソッド
- 何も指定しないと空白文字(スペース、タブ、改行)で文字列を分割する
- 例
~~~python
文字列型変数.split()
~~~

## map関数
- 指定した関数をリストやタプルなどの各要素に適用することが出来る
- 例
~~~python
map(適用したい関数、適用されるリストやタプル)
~~~

## リストの変数への代入
~~~python
a,b = [1, 2]
~~~

## タプル,リスト,配列,構造体の役割の整理
| 種類   | 特徴                                                                 | 変更可能性 | 使用例               |
|------|--------------------------------------------------------------------|------|------------------|
| タプル  | 複数の異なる型の要素を持つことができる。要素の追加や削除ができない。                                      | 不可   | (1, 'a', 3.14)   |
| リスト  | 複数の同じ型または異なる型の要素を持つことができる。要素の追加や削除が可能。                                 | 可能   | [1, 2, 3]        |
| 配列   | 同じ型の要素を持つことができる。固定長または可変長。要素の追加や削除が可能。                                 | 可能   | array('i', [1, 2, 3]) |
| 構造体  | 異なる型の要素を持つことができる。フィールド名でアクセス。要素の追加や削除が可能。                           | 可能   | struct.Struct()  |

## formatメソッド
- `format` メソッドは、文字列の中に変数や値を埋め込むために使用されるメソッドです。
- 中括弧 `{}` をプレースホルダーとして使用し、`format` メソッドの引数に埋め込みたい値を渡します。
- 例
~~~python
name = "Alice"
age = 30
formatted_string = "Name: {}, Age: {}".format(name, age)  # "Name: Alice, Age: 30" という文字列が formatted_string に代入される
~~~
