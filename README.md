# codebuild-sandbox
## メモ
```
$ aws codebuild create-webhook --cli-input-json file://inputs-create-webhook.json
で webhook の登録まで自動でやってくれる
codebuild の source が GitHub か GitHub Enterprise かで、secret が返ってくるか異なる？
https://docs.aws.amazon.com/cli/latest/reference/codebuild/create-webhook.html

https://docs.aws.amazon.com/ja_jp/codebuild/latest/userguide/sample-github-enterprise.html
> [ウェブフックの作成] ダイアログボックスが表示されるのは 1 回だけです。ペイロード URL とシークレットキーをコピーします。GitHub Enterprise にウェブフックを追加するときにこれが必要となります。
ぽい
```
