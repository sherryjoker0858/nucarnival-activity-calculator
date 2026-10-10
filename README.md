# 新世界狂歡活動計算機

## 部署到 GitHub Pages
1. 在 GitHub 建立一個新的 repository，例如 `nucarnival-activity-calculator`。
2. 上傳 `index.html`（也可將 ZIP 解壓後上傳）。
3. 進入 repository 的 **Settings → Pages**。
4. 在 **Build and deployment** 選擇 **Deploy from a branch**。
5. Branch 選 `main`，資料夾選 `/(root)`，按 Save。
6. 等待部署完成，GitHub 會顯示網站網址。

## 使用提醒
- 「虛擬性悖論」為預設活動，日期預設為 2026/10/01–2026/11/05。
- 關卡積分與獎勵門檻是可編輯的示範值，不是官方確認數值；請依遊戲內資訊輸入。
- 關卡加成以百分比輸入，計算公式為基礎積分 × (1 + 加成百分比 / 100)。
- 活動、進度、關卡、獎勵資料存在瀏覽器 localStorage。請定期匯出 JSON 備份。
- 這是粉絲自製工具，非官方產品。
