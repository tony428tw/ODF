# ODF 開放文件格式｜介紹與應用

![ODF 開放文件格式介紹與應用](./ODF_COVER.png)

一個以校園推廣為主題的 ODF（Open Document Format）介紹網站，協助學生、教師與行政人員快速了解開放文件格式、免費編輯工具及政府文件格式政策。

## 網站內容

- ODF 核心價值：跨平台、長期保存、資訊自主與協作共通
- 常用格式：`.odt` 文書、`.ods` 試算表、`.odp` 簡報
- 學生、教師與行政人員的校園應用情境
- 數位發展部 ODF 文件應用工具及免費軟體下載
- 可編輯文件使用 ODF、不可編輯文件使用 PDF 的判斷指南
- 公文附件轉檔步驟、操作手冊與常見問題
- ODF 校園推廣影片與完整教材

## 預覽網站

這是純靜態網站，不需安裝套件或建置工具。

```bash
python -m http.server 4173
```

啟動後開啟 `http://127.0.0.1:4173/`，也可以直接開啟 `index.html` 瀏覽。

## 專案結構

```text
.
├── index.html          # 網站內容與語意結構
├── styles.css          # 視覺設計與響應式版面
├── script.js           # 行動選單及頁籤互動
├── ODF_COVER.png       # GitHub README 封面
├── ODF介紹與應用.pdf   # 完整推廣教材
└── 朝陽校園照片/       # 網站使用的校園影像
```

## 設計與功能

- 響應式單頁網站，支援桌機、平板與手機
- 鍵盤可操作的導覽與校園情境頁籤
- `focus-visible` 焦點樣式與跳至主要內容連結
- 支援 `prefers-reduced-motion`
- 可水平捲動的手機版軟體下載表格
- YouTube 隱私強化模式嵌入影片
- 無框架、無第三方前端相依套件

## 重要資源

- [政府文件標準格式（ODF-CNS 15251）實施計畫（113–116 年）](https://www-api.moda.gov.tw/File/Get/moda/zh-tw/mi8j83yBxg7gRfF)
- [數位發展部 ODF 文件應用工具與學習資源](https://moda.gov.tw/digital-affairs/digital-service/app-services/248)
- [LibreOffice 正體中文網站](https://zh-tw.libreoffice.org/)
- [Apache OpenOffice 正體中文網站](https://www.openoffice.org/zh-tw/)
- [ODF 介紹與應用影片](https://youtu.be/aUBvtWaOY3w)

## ODF 是什麼？

ODF 是符合我國國家標準 CNS 15251、對應 ISO/IEC 26300 國際標準的開放文件格式。公開的格式規格讓使用者能自由選擇軟體與作業平台，也有利於文件交換及長期保存。

| 格式 | 用途 |
| --- | --- |
| `.odt` | 文書、報告、會議紀錄 |
| `.ods` | 試算表、統計與資料分析 |
| `.odp` | 簡報、課堂與專題發表 |

## 授權與素材

網站內容以 ODF 教育推廣為目的。政府政策、軟體名稱及外部資源之權利歸原發布單位所有；校園照片及專案內教材請依原始授權範圍使用。
