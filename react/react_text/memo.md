# いまどきのJSプログラマーのためのNode.jsとReactアプ…発テクニッ
# memo

##virtualDOMとは
ツリー構造のHTMlを覚えて、更新前と更新後の差分だけを変更することができる

# 使ったメソッド
- substr(start, to)
  takumi = "abced"

  takumi.substr(1, 3)としたとき
  出力は
  bceとなる

# Componentについて
- 部品を作成するイメージ
- それらを使いたい所で使いまわす

## メリット
- メンテがしやすい
- 要素を簡単に追加することができる


ReactDOM.render(1, 2)
第一引数は表示したい要素
第二引数は表示したい場所のセレクタ

# コンポーネントの状態管理
- setStateメソッドをcontructorに定義
- setStateメソッドで値を渡す
- そのメソッドが呼び出されることでrenderが呼ばれ、値が再描写される



# propsについて
- 基本的に読み取り専用である、値は変更しないこと

# state
- 値の状態を変更し、renderで再描写
