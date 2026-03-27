# Enter IMC · 客戶報告入口站

> 確認鍵智創科技股份有限公司 · GEO / SEO 健檢報告 · 策略計畫

本站透過 GitHub Pages 部署，提供客戶報告的線上瀏覽連結。

## 📁 目錄結構

```
enterimc-reports/
├── index.html              ← 報告總覽首頁
├── reports/                ← 所有客戶報告 HTML 檔
│   └── FansFeed_GEO_audit_20260327.html
└── README.md
```

## ➕ 新增客戶報告步驟

1. 將新報告 HTML 檔放入 `reports/` 資料夾
2. 在 `index.html` 的 `#cardGrid` 區塊新增一張 card（複製現有 card 格式修改）
3. `git add . && git commit -m "新增 XXX 報告" && git push`

## 🚀 GitHub Pages 設定

Settings → Pages → Source: `Deploy from a branch` → Branch: `main` / `(root)`

公開網址：`https://{你的帳號}.github.io/enterimc-reports/`
