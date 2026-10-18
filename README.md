# QELVORN Hub

QELVORNが開発するDiscord Botと関連情報をまとめる公式ポータルの静的サイトです。

## 構成

- `index.html` — ページ構造、スタイル、Bot検索・フィルター・詳細モーダルを含む初期版
- HTML / CSS / JavaScriptのみで動作し、ビルドツールやサーバーは不要です

## ローカルで確認

`index.html` をブラウザで開いてください。

## Cloudflare Pagesで公開

1. Cloudflareダッシュボードを開き、Workers & Pages に移動します。
2. Pagesプロジェクトを作成し、GitHubリポジトリ `yajuusennpai631-dotcom/qelvorn-hub` を接続します。
3. フレームワークプリセットは **None** を選びます。
4. ビルドコマンドは空欄、ビルド出力ディレクトリは `/`（リポジトリのルート）に設定します。
5. デプロイを実行します。

設定画面の選択肢はCloudflareの現在のUIに応じて確認してください。独自ドメインは任意で後から追加できます。

## Bot情報の更新

`index.html` 内の `bots` 配列を編集し、各Botの実際の機能、公開状態、正しい招待URLを確認したうえで追加してください。未確認の機能やリンクは推測で掲載しないでください。

## 公式リンク

- QELVORN website: https://qelvorn.mrag.workers.dev/
- Discord: https://discord.gg/QtbbGjCk
- FANBOX: https://qelyvorn.fanbox.cc/
