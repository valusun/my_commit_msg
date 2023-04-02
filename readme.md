# 自分のためのcommit-msg

## 使い方

1. `commit-msg`ファイルをコピーして下記に置く  
`./git/hooks/commit-msg`

## コミットメッセージの書き方

`prefix/コミットメッセージ`の形式で書く  

現時点で`prefix`は、下記の3パターンに対応している。

1. `add`
2. `update`
3. `remove`
4. `fix`

### 例

- `add/設定ファイルの作成`  
- `update/テストの更新`  
- `remove/レガシー機能の削除`  
- `fix/○○機能のバグ修正`
