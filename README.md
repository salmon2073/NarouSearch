# NarouSearch
「小説家になろう」に公開されている小説の全文検索システム

## 言語(予定)
Python

## 検索プロセス(ユーザ -> システム)
* 検索する小説をurlで指定 -> クロールしてリンクを抽出
* 検索キーワードを入力 -> 各リンクから検索
* 結果の閲覧 -> 前後の文と合わせてハイライト表示

## 課題
* リクエスト間隔をどうするか
