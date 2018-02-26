# RubyKeywordArgument
キーワード引数

## 処理
変数の有効範囲を理解するため、それぞれに変数aを定義して確認する。

## コード
```
def introduce(name = "ほにゃらら")
    puts "私は#{name}です。"
end

introduce("私")
introduce()
```

## 出力結果  
```
変数aは5です。
変数aは10です。
変数bは20です。
合計は30です。
```
  
## 開発環境
| 開発ツール |  |
|:-|:-|
| OS | Windows10 |
| 仮想化ソフト | Oracle VM VirtualBox 5.2 |
| 構築ソフト | Vagrant 2.0.2 |
| 仮想化上OS | CentOS 6.9 |
| SSHクライアント | PuTTY 0.6.8 |
| FTPクライアント | Cyberduck 6.3.5 |
| エディタ | Atom 1.24.0 |
| 開発言語 | Ruby 2.4.0 |
