# 🥪 Subway Calculator

Unofficial mobile-first calorie and protein calculator for 6" Subway® subs, with an iOS-inspired UI.  
非官方的 Subway® 潛艇堡熱量與蛋白質計算器，以手機體驗為核心，帶有 iOS 風格互動。

> ⚠️ **Unofficial project.** Not affiliated with, endorsed by, or sponsored by SUBWAY® or Subway IP LLC. "SUBWAY" is a trademark of its respective owner and is used here only to describe what this tool calculates.  
> ⚠️ **非官方專案。**與 SUBWAY® 無任何關聯，未經其授權或背書。「SUBWAY」為其權利人之商標，此處僅用於說明本工具的用途。

## 🚀 Live Demo / 線上版本

https://thom436.github.io/subway-calculator/

## ✨ Features / 功能特色

- Flavor picker with grouped modal list + kcal hints  
  主餐口味使用分組彈窗清單，可直接看到各口味熱量

- Real-time nutrition summary  
  即時計算總熱量（kcal）與蛋白質（g）

- Add-ons flow optimized for mobile  
  加料支援快速新增、替換、刪除，流程更直覺

- Two-sauce support with auto split logic  
  支援第二種醬料，兩種醬料會自動平分熱量

- Optional sauce mode  
  可不選醬料（No sauce），不影響主餐與加料計算

- Dark mode + iOS-like motion feedback  
  深色模式與按鈕/切換動畫，提升操作手感

## 🧮 Calculation Rules / 計算規則

- Base: selected 6" sandwich  
  基礎：以所選 6 吋主餐為基準

- Double meat: adds corresponding add-on nutrition (if available)  
  雙份肉：若有對應加料資料，會額外加上該品項營養值

- Add-ons: summed by selected items  
  加料：依已選加料逐項加總

- Sauces:  
  醬料：
  - 1 sauce: full sauce kcal  
    一種醬料：計入完整熱量
  - 2 sauces: each counted as 1/2  
    兩種醬料：各以 1/2 熱量計入
  - No sauce: 0 kcal from sauces  
    不加醬：醬料熱量為 0

## 🛠️ Tech / 技術

- Vanilla HTML / CSS / JavaScript  
  原生 HTML / CSS / JavaScript

- Static hosting via GitHub Pages  
  使用 GitHub Pages 靜態部署

## 📦 Local Development / 本機開發

Open `index.html` directly in browser, or run a local static server.  
可直接用瀏覽器開啟 `index.html`，或使用本機靜態伺服器。

Example / 範例：

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.  
接著開啟 `http://localhost:8080`。

## ⚠️ Disclaimer / 聲明

This is an independent tool and is not affiliated with SUBWAY®.  
Nutrition values are estimates and may vary by store and preparation.

本工具為非官方計算器，與 SUBWAY® 無關。  
營養數據為估算值，可能因門市與製作方式有所差異。

Nutrition source: [SUBWAY Taiwan official nutrition page](https://subway.com.tw/GoWeb2/include/meals-nutrition.html).  
營養資訊來源：[SUBWAY 台灣官方營養資訊](https://subway.com.tw/GoWeb2/include/meals-nutrition.html)。  
Data version: 2026-03-31 (manually curated).  
資料版本：2026-03-31（手動整理）。
