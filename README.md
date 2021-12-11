# TODOO

![Screenshot](https://cdn-ak.f.st-hatena.com/images/fotolife/h/ha2zakura/20200102/20200102173744.png)

https://todoo.nombi.info/  
github.ioから，すぐ使えます．

## What's this?
TODOOは，進捗を量で見るTODOリストです．「なにをやるか」ではなく，「どれだけやるか」を重視します．  

自分用に作ったので，そこまで作り込んでいません．特に長文にするとレイアウトが崩れやすいです．

## What's it made of?
~~xiuposの時間~~ Vue.jsでできています．  

基本的なシステムは[このQiita記事](https://qiita.com/moonglows76/items/358ef3cd1566c38ece3a)をほとんどそのまま使ってます．コピペではないです．  
Codeはとても読めるものではないと思いますが，主なコードは `/src/App.vue`で見れます．  

## How to use?

### タスクの作成

1. 左のテキストボックスにタスクの名前をいれます．  
(ここで長すぎると，レイアウトが崩れます()．短かく，端的に)

1. 中央のテキストボックスにページ数や工程数などの「量」をいれます．  
(完了するまでタスクは削除できないので，現実的な量にしましょ)

1. 右のボタンをおして作成!

### タスクの完了

1. タスクの右側のボタンで完了数の増減ができます．

### タスクの削除

1. 完了したものだけを一番下のボタンで消せます．

## How to save?

[LocalStorage](https://www.w3schools.com/html/html5_webstorage.asp)を使ってます．  
なので，他人にTODOOを覗き見られることはありません．
