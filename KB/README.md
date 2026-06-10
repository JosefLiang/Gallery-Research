# KB — 案例知識庫

本資料夾存放經 LLM 萃取完成的美術館建築案例知識卡。每一個 Markdown 檔案對應一個案例，格式統一，方便後續 RAG 或直接查詢。

## 資料夾結構

```
KB/
├── README.md            ← 本檔案
├── index.md             ← 所有案例索引
└── cases/
    ├── 01_guggenheim_bilbao.md
    ├── 02_fondation_louis_vuitton.md
    ├── 03_museo_soumaya.md
    ├── 04_chichu_art_museum.md
    ├── 05_kiasma.md
    ├── 06_kunsthaus_bregenz.md
    ├── 07_clyfford_still_museum.md
    ├── 08_tate_modern.md
    ├── 09_zeitz_mocaa.md
    ├── 10_lenbachhaus.md
    ├── 11_maxxi.md
    ├── 12_the_broad.md
    ├── 13_de_young_museum.md
    ├── 14_national_museum_qatar.md
    ├── 15_benesse_house.md
    ├── 16_maat_lisbon.md
    ├── 17_louvre_pyramid.md
    ├── 18_jewish_museum_berlin.md
    ├── 19_musee_confluences.md
    └── 20_chimei_museum.md
```

## 知識卡欄位說明

| 欄位 | 說明 |
|------|------|
| `案例名稱` | 美術館正式名稱（中英文） |
| `建築師` | 設計建築師 |
| `地點` | 國家 · 城市 |
| `年份` | 完工年份 |
| `規模` | 面積（m²）/ 樓層 |
| `設計策略主題` | 對應六大主題之一 |
| `核心設計手法` | 3–5 個關鍵字標籤 |
| `設計策略說明` | 建築師的核心設計邏輯（150–200 字） |
| `可應用的設計概念` | 轉化為設計原則的學習重點 |
| `關鍵字` | 供搜尋用的索引標籤 |
