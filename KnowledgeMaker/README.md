# KnowledgeMaker — 案例萃取 Prompts

本資料夾存放用於 LLM 萃取美術館案例資料的 prompt 模板（AI 小精靈）。

## 使用流程

```
原始資料（文章 / PDF / 網頁）
        ↓
  extraction_prompt.md    ← 單一案例萃取
        ↓
   KB/cases/*.md          ← 輸出格式
        ↓
  batch_template.md       ← 批次萃取多案例
```

## 檔案說明

| 檔案 | 用途 |
|------|------|
| `extraction_prompt.md` | 從原始資料萃取單一案例的完整 prompt |
| `batch_template.md` | 批次萃取多個案例的 prompt 模板 |
| `field_definitions.md` | 各欄位的精確定義與範例 |
