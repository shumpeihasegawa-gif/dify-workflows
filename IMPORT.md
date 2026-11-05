# Difyへのインポート

Difyのアプリ作成画面で「アプリをインポート」→「URLから」を選び、次のURLを貼り付けてください。

https://raw.githubusercontent.com/shumpeihasegawa-gif/dify-workflows/main/insurance-balance-demo.yaml

「人間の入力」ノードに対応するDify環境が必要です。依存プラグインはMarkdown Exporter 4.0.0（bowenliang123）です。インポート時に案内が出たら導入してください。モデル・外部APIキーの設定は不要です。

架空のデータを使用する検証用アプリです。DEMO-005、処理日2026-11-04を選び、チャットを開始して「開始」と送信します。点検担当A〜Eを工程に合わせて選択し、確認済を選んで承認してください。

状態は実行単位、再作成は1回までです。実際の発送や社内システム更新は行いません。Excelファイルを実行時に読み込む方式ではなく、サンプルデータと固定ルールをフロー内に組み込んでいます。
