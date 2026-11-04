# ChaTraMue × 拉亞漢堡　泰奶聯名　社群操作 / Thai Tea Social Ops

手標 ChaTraMue × 拉亞漢堡 台泰聯名活動社群操作排程表（三環五線）· 中英雙語。
Bilingual (繁中 / EN) social ops schedule for the ChaTraMue × Laya Burger Thai-milk-tea collab.

- **檔期 / Window**：12/2 記者會 → 12/3 上市 → 12/4–20 擴散
- **五線 / Lines**：外環 泰國・中環 台灣泰國人・內環 KOL＋KOC・拉亞官方・foodpanda 通路
- **語言 / Language**：頁面最上方「中文 / EN」標籤一鍵切換；選擇記在本機。
- **功能 / Features**：卡片即時編輯、新增／刪除、跨日跨環搬移（點 ⇅ 或桌機拖曳）、lane 開關、複製排程、匯出 JSON；變更自動存於瀏覽器本機。

## 協作機制 / Workflow（重要）

**單一真相來源 = 本 repo `main` 分支的 `index.html`。** 排程內容寫在檔案裡的 `SEED` 資料，不靠網頁暫存。

- **要改內容**：於對話中請 Claude 修改 → Claude `git fetch` 併入最新 → 改 `index.html` → push 到 `main`。團隊亦可直接改檔或開 PR，commit 到 `main`。
- **網頁上的「編輯」只是本機草稿**，不會寫回 repo。要讓草稿進正式版，按頁面 **「匯出 JSON」** 複製整份資料，貼回對話交給 Claude 寫入 `index.html`。
- **同步**：需要時請 Claude「同步最新版」，Claude 會 `git fetch origin main` 取最新 commit 後接手。
- **衝突**：若同時多方修改，Claude 會先 fetch、手動併好再 push，不硬蓋團隊的 commit。

> Source of truth is `index.html` on `main`. In-page edits are local drafts only — use **Export JSON** and paste back to Claude to make them official. Ask Claude to “sync latest” to pull the newest commit.

## 使用 / Usage
瀏覽器開啟 `index.html` 即可（或透過 GitHub Pages 發佈）。Open `index.html` in a browser, or publish via GitHub Pages.
