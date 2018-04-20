# gas-slack-log-spreadsheet

[motemen様のブログ](https://motemen.hatenablog.com/entry/2015/11/gas-slack-log-spreadsheet)
を拝読させていただきましたが、スプレッドシートの1ファイル200万カラム制約に引っかかるため、月単位ではなく日単位でファイルを生成するように変更。

GAS上に設置する場合、上記ブログにある通り [app.js](https://github.com/doTechHub/gas-slack-log-spreadsheet/blob/master/app.js)を新規プロジェクトのコードとしてコピペして `slack_api_token` をスクリプトのプロパティに設定するだけで動きます。

※slackのAPIトークンは[ここ](https://api.slack.com/custom-integrations/legacy-tokens)から確認できます。
