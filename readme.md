# 自分のためのcommit-msg

## 使い方

1. 同ディレクトリの`commit-msg`をコピーして下記に置く  
`./git/hooks/commit-msg`

## コミットメッセージの書き方

`prefix/コミットメッセージ`の形式で書く  

現時点で`prefix`は、下記の3パターンに対応している。

1. `add`
2. `update`
3. `remove`

### 例

- `update/テストの追加`  
- `add/設定ファイルの作成`  
- `remove/レガシー機能の削除`  
