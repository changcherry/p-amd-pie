# 善盾 AI

長者防詐實境陪練平台。這個 repository 目前收錄可操作的 Next.js 產品展示版，包含四種詐騙情境、訓練互動、六項能力報告、歷史記錄與情境管理畫面。

## 本機啟動

```bash
cd frontend
npm ci
npm run dev
```

開啟 <http://localhost:3000>。

## 檢查

```bash
cd frontend
npm run lint
npx tsc --noEmit
npm run build
```

> 目前版本的情境、登入、評分與歷史資料為展示流程；MongoDB、正式認證與 AI API 尚待後續階段串接。
