# microcourse｜互動式微單元課程

**microcourse** 是一套 [Agent Skill](https://agentskills.io/specification)，協助 AI 將教材整理成**視覺化、可操作、依知識主題編排的微單元教學網站**，而不是逐頁照搬投影片。

## 快速開始

1. **準備 Skill**：下載本儲存庫，將整個 `microcourse/` 資料夾放在 AI 可以讀取的位置；若工具支援 Agent Skills，也可依該工具的方式安裝。
2. **提供教材**：上傳 PPT 等教材文件、已取得的授課逐字稿，或兩者組合。
3. **複製指令**：

```text
請先讀取 microcourse/SKILL.md，並依照其規範，將我提供的教材製作成完整、可使用的互動式微單元課程。
```

若使用 **ChatGPT Library**，只需將指令中的路徑改為 `Library/microcourse/SKILL.md`；其他環境則依實際存放位置調整。

## 使用須知

- 每個單元以**明確的主題**為優先，參考時間預設約 5 分鐘，不強制湊滿或截斷。
- 可單獨使用教材或逐字稿；**不支援直接解析原始影片或自動產生逐字稿**。
- 這是提供 AI 遵循的製課規範，**不是獨立執行的轉檔工具**；檔案讀取與網站產生能力取決於所用 AI。

AI 的執行入口是 [`SKILL.md`](SKILL.md)，細部規則位於 [`references/`](references/)。
