# 植物ノート 🌿

植物を撮影してAIで判定・クラウドに記録するWebアプリです。

## 機能
- 📷 写真を撮影してAI（Claude）で植物を判定
- ☁ 画像をCloudinaryにクラウド保存
- 🔄 GitHub Gistでデータを端末間同期
- 🗺 撮影位置を地図で確認
- 📱 PWA対応（ホーム画面に追加可能）

## セットアップ

アプリを開いて「⚙️ 設定」タブから以下を設定してください。

1. **Anthropic APIキー** — [console.anthropic.com](https://console.anthropic.com)
2. **Cloudinary** — [cloudinary.com](https://cloudinary.com) に無料登録してCloud nameとUpload presetを取得
3. **GitHub Gist** — [github.com/settings/tokens](https://github.com/settings/tokens) でgistスコープのトークンを作成

## デプロイ

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new)

このリポジトリをVercelにImportするだけでデプロイできます。
