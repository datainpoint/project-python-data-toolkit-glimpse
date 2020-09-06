# 如何對資料框進行基礎操作

> 寫一些 pandas 語法操作 Johns Hopkins COVID-19 每日報告。

點擊圖示啟動專案 [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/datainpoint/project-pd-basic-manipulations/master?filepath=project-pd-basic-manipulations.ipynb)

## 標籤

- 程式設計
- 獲取載入
- 整併轉換

## TL; DR

在這個專案中，我們打算寫一些 pandas 語法操作約翰霍普金斯大學 COVID-19 Data Repository 中最新的每日報告，讀者將學會如何定義函式 `get_latest_daily_report()` 將約翰霍普金斯大學 COVID-19 Data Repository 中最新的每日報告載入成為資料框、如何衍生新的欄位（衍生治療中案例數）、選擇特定欄位（選擇一個或多個）、篩選指定觀測值（台灣在哪裡）、分組摘要（以國家為單位聚合確診數）以及排序（將摘要結果由大到小遞減排序）。