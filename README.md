# 🎬 字幕國際化自動化工作流
**Google Drive × n8n × AI 翻譯 × SRT 時間軸處理**

---

## 背景與痛點

媒體公司製作國際版內容時，需要人工處理 SRT 字幕檔的翻譯與時間軸整理，逐行對照耗時，且容易造成時間軸錯位。

## 解決方案

1. 自動偵測 Google Drive 新增的 SRT 字幕檔
2. 解析時間軸與字幕內容，分離主旨與時間碼
3. AI 翻譯字幕內容並分析時間軸重點
4. 整理後自動上傳回 Drive，更新影片說明欄，LINE 通知完成

## 實際成果

- ✅ 字幕處理效率提升 75%
- ✅ 自動更新檔名與說明欄，零人工後處理
- ✅ 目前於媒體公司實際運行中

## 技術棧

`n8n` `Google Drive API` `SRT 解析` `AI 翻譯` `LINE Messaging API` `Schedule Trigger`

---
*Built by Sam｜AI Automation Engineer*
