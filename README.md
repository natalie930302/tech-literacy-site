# tech-literacy-project

科技素養主題網站,2024 年中起步、2025 年初仍有更新。

## 技術棧

Next.js + TypeScript,含網站地圖設定(`next-sitemap.config.js`)。

## 開發

```bash
npm install
npm run dev
```

瀏覽器開啟 [http://localhost:3000](http://localhost:3000)。

> ⚠️ 本專案 git 歷史中曾經不小心把 `.env` 環境變數 commit 進版控,後來已自行發現並修正(commit:「Remove committed environment secrets and add safe template」)。若要重新部署,請確認金鑰皆已改用你自己的新值。
