# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？

・リモートリポジトリ
　　ネット上に配置する複数人で共有するためのリポジトリ

・ローカルリポジトリ
　　開発者が一人で使用するために自分のPC上に配置するリポジトリ

## プッシュとマージの違いは何でしょうか？

プッシュはローカルリポジトリの内容をリモートリポジトリに保存させるもの。
マージは今いるブランチに別のブランチの変更履歴を取り込むもの。

## コミットとプッシュの違い

・コミットはローカルリポジトリに変更内容を保存するもの

プッシュはローカルリポジトリの内容をリモートリポジトリに保存させるもの。

## コミットのメッセージはどのように書いてあげるのが最適でしょうか？

プロジェクトのチームのルールに則り、編集内容を正確にわかりやすく書くこと。

## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？

ローカルでマージをすると、ブランチにすぐに反映される。
プルリクエストをすると、マージをする前に第三者のチェックが入るため、自分では気づかなかったバグなどが発見しやすい。


## コンフリクトを起こしてしまった場合、どう対処すべきですか？

ソースコードの内容やその意図を把握する必要があるため、ソースコードを書いた人と相談をしながら作業を進める。