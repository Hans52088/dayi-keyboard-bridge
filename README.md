# ⌨️ 大易實體鍵盤轉接器 (Dayi Keyboard Bridge)

一個專為 iPad 及移動設備設計的**大易輸入法實體鍵盤轉接工具**，讓您在任何瀏覽器中使用實體鍵盤進行大易輸入。

## ✨ 線上體驗

👉 **[立即使用（GitHub Pages）](https://hans52088.github.io/dayi-keyboard-bridge/Dayi-ActualKB-transfer(Offline).html)**

> iPad 用戶：在 Safari 中開啟上方連結，點擊分享 ⬆️ →「加入主畫面」，即可永久離線使用！

## 🌟 特色

- **18,636 字**完整大易四碼字庫，內嵌於單一 HTML 檔
- **零啟動延遲** — 字典以極速字串查詢方式運作
- **100% 離線** — 加入主畫面後無需網路
- **完美 PWA 支援** — 內建 Service Worker 自動快取，斷網重開也能正常運作
- **現代介面** — 磨砂玻璃質感設計，適配深色模式
- **iPad 最佳化** — 完美搭配實體鍵盤使用

## 💡 快速使用指南

1. **大易輸入**：使用實體鍵盤的英文模式打字，程式會根據大易字根將其組合為中文字。
2. **一鍵複製**：打完整句話後，按下 **Enter** 鍵。
3. **自動處理**：系統自動複製到剪貼簿，並清空輸入區。
4. **切換貼上**：切換到目標 App，直接 **貼上** 即可。

## ⌨️ 按鍵對照

| 按鍵 | 功能 |
|------|------|
| `A-Z / 0-9` | 輸入大易字根 |
| `Space` | 選第 1 個候選字 |
| `'` | 選第 2 個候選字 |
| `[` `]` `-` `\` | 選第 3-6 個候選字 |
| `=` | 進入/退出標點模式 |
| `Enter` | 複製全部文字並清空 |
| `Backspace` | 刪除 |

## 📦 版本說明

| 版本 | 檔案 | 說明 |
|------|------|------|
| **離線完整版** | [`Dayi-ActualKB-transfer(Offline).html`](Dayi-ActualKB-transfer(Offline).html) | 單檔 PWA，內嵌完整字庫 |
| 半離線版 | [`index_semi_offline.html`](index_semi_offline.html) | 從線上下載字典後快取在 LocalStorage |

詳細說明請參閱：
- [離線版 README](README_OFFLINE.md)
- [半離線版 README](README_SEMI_OFFLINE.md)

## 📲 iPad 安裝方式

1. 在 iPad 的 **Safari** 中開啟上方「立即使用」連結
2. 點擊底部 **分享按鈕** ⬆️
3. 選擇 **「加入主畫面」**
4. 完成！(具有 PWA 自動快取機制，即使後續斷網或關閉重新打開，也能順利載入使用)

> ⚠️ 注意：iPad「檔案」App 的預覽功能不支援 JavaScript，請務必透過 Safari 使用。

---
製作者：WHY | 字庫來源：[dayi4.dict.yaml (Rime)](other/dayi4.dict.yaml)
