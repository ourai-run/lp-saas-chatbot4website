# ourai チャットボット — ランディングページ (LP)

「ourai チャットボット」の製品紹介ランディングページ。
営業資料 `ourai_chatbot_営業資料_v0.2.pptx` の内容をベースに構成。

- **依存ゼロ・ビルド不要の静的サイト**（HTML + CSS のみ）
- ブランド配色：コーラル `#F96167` / ネイビー `#16233A` / ゴールド `#FBBF24`
- 想定ドメイン：`ourai.run`

## 構成

```
index.html      ... ページ本体（全セクション）
styles.css      ... スタイル（ブランド配色・レスポンシブ）
assets/logo.png ... ロゴ
```

セクション順：ヒーロー → お悩み → 解決（チャットUIモック）→ 3つの理由 → 仕組み → 安心 → 活用業種 → 料金 → CTA。

## ローカルで確認

`index.html` をブラウザでダブルクリックで開くだけ（サーバー不要）。

## デプロイ

ビルド不要なので、そのまま静的ホスティングに乗ります。

- **Vercel**：このリポジトリを接続 → フレームワークは「Other」/ビルドコマンドなし/出力ディレクトリ `./` で自動公開。独自ドメイン `ourai.run` を割り当て。
- もしくは `index.html` 一式をドラッグ&ドロップ（Vercel / Netlify / Cloudflare Pages 等）。

## 編集メモ

- 文言は `index.html`、見た目は `styles.css`。
- 問い合わせ先：`support-chatbot@ourai.run`（`mailto:` リンクで各CTAに設定済み）。
- 将来マーケページを増やす場合は Next.js / Astro 化も可能（現状は1ページのため静的が最軽量）。

## 連絡先

support-chatbot@ourai.run
