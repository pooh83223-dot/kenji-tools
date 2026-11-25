# kenji-tools — 我的工具總專案

## 對話開始時請先讀
進度與最近更動都在 Obsidian：`secondbrain/kenji-tools/工作筆記.md`

## 工作模式
- **加新工具**：對 Claude 說「我想做一個 XXX 工具」→ Claude 會建 `tools/<工具名>/` 子資料夾並引導製作
- **結束工作**：對 Claude 說「**收工**」→ 自動 commit + push + 更新 Obsidian 工作筆記
- **接續工作**：對 Claude 說「**開工**」或「讀工作筆記、告訴我上次做到哪」

## 工作桌 + 三個家
- 📋 GDrive 工作桌：`G:\我的雲端硬碟\kenji-tools\`（自動跨電腦同步）
- 🐙 GitHub repo：`pooh83223-dot/kenji-tools`（公開，網頁的家，Pages：https://pooh83223-dot.github.io/kenji-tools/）
- 📘 Obsidian 駕駛艙：`secondbrain/kenji-tools/工作筆記.md`（想法的家）
- 🔥 Firebase 專案：`my-tools-11a8a`（資料的家；規則檔在 `C:\Claude_use\初期規則架設\firebase-my-tools\`）
- 🗄️ Supabase 專案：`pooh83223-dot's Project`（ref `nfvcfouichebxgshxcmj`）

## 工具清單
（之後加新工具時會自動更新）
- （尚無）

## 工作注意事項
- 個人或他人資料一律去識別化
- API Key（Gemini 等）只放環境變數，絕不寫進程式碼或推上 GitHub
- commit 訊息要寫清楚做了什麼 + 為什麼
- 回答用繁體中文、白話易懂
- 收工前說「收工」讓 Claude 同步三方
