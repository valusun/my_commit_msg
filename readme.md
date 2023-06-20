# 自分のためのcommit-msg

## 使い方

1. `commit-msg`ファイルをコピーして下記に置く  
`./git/hooks/commit-msg`

## commit-msg

決まった形式でcommitメッセージを書くことを強制し、commitメッセージを整えてくれる。  

### コミットメッセージの書き方

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
- `fix/機能のバグ修正`

※動かない場合は、実行権限を与えてみてください。  
`chmod +x commit-msg`

## commit-msg_issue  
  
上記に加え、issue番号の入力を強制化させたもの。  

### コミットメッセージの書き方

`prefix/issue番号/コミットメッセージ`の形式で書く  

### 例  

- `add/1/issue番号を強制化するcommit-msg追加`

### 注意点  

このcommit-msgを使う際には`hooks`直下に置いた後、ファイル名を`commit-msg`にしてください。  
