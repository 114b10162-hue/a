# 醫院評鑑管理漫畫項目

利用 AI Agent (baoyu-comic) 創建的醫院評鑑管理知識漫畫。

## 項目概述

- **主題**：醫院評鑑管理
- **格式**：6頁少女漫畫風格
- **工具**：baoyu-comic AI Agent
- **語言**：中文

## 項目結構

```
.
├── README.md                      # 項目說明
├── config/
│   └── comic-config.yml          # 漫畫配置文件
├── content/
│   ├── script.md                 # 漫畫腳本和大綱
│   └── source-material.md        # 醫院評鑑管理參考資料
├── output/
│   └── hospital-accreditation-comic.md  # 最終輸出
└── docs/
    └── usage.md                  # 使用指南
```

## 快速開始

### 前置要求

- 安裝 Node.js 環境
- 安裝 baoyu-comic skill

### 安裝 baoyu-skills

```bash
npx skills add jimliu/baoyu-skills
```

### 生成漫畫

```bash
# 使用少女漫畫風格生成 6 頁漫畫
/baoyu-comic content/script.md --style shoujo --lang zh

# 或使用完整選項
/baoyu-comic content/script.md \
  --art manga \
  --tone romantic \
  --layout standard \
  --lang zh
```

## 配置選項

### 畫風（Art Style）

- `manga` - 日漫風格（推薦用於少女漫畫）
- `ligne-claire` - 歐洲漫畫風格
- `realistic` - 寫實風格
- `ink-brush` - 水墨風格
- `chalk` - 粉筆風格

### 基調（Tone）

- `romantic` - 浪漫、唯美（少女漫畫常用）
- `warm` - 溫暖、懷舊
- `dramatic` - 高對比、緊張
- `energetic` - 活力、動感
- `neutral` - 平衡、理性

### 布局（Layout）

- `standard` - 標準 4-6 分鏡（推薦）
- `cinematic` - 戲劇性 2-4 分鏡
- `dense` - 密集 6-9 分鏡
- `splash` - 1-2 大圖
- `mixed` - 混合 3-7 分鏡

## 項目進度

- [ ] 創建內容腳本
- [ ] 配置漫畫參數
- [ ] 生成漫畫圖片
- [ ] 審核和調整
- [ ] 最終發布

## 相關資源

- [baoyu-skills 文檔](https://github.com/JimLiu/baoyu-skills)
- [baoyu-comic 用法指南](https://github.com/JimLiu/baoyu-skills/blob/main/README.zh.md#baoyu-comic)

## 許可證

MIT
