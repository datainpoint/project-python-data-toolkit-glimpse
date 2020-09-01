# 冠狀病毒大流行

> 寫一些 Python 程式擷取摘要冠狀病毒大流行現況的四個關鍵數字，並且像維基百科一般地描述。

點擊圖示啟動專案 [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/datainpoint/project-covid-19-pandemic/master?filepath=project-covid-19-pandemic.ipynb)

## 標籤

- 獲取載入
- 整併轉換
- 摘要探索

## TL; DR

我們定義了一個函式 `get_latest_daily_report()` 將約翰霍普金斯大學 [COVID-19 Data Repository](https://github.com/CSSEGISandData/COVID-19) 中最新的每日報告載入成為資料框，並從資料框中將四個關鍵數字摘要出來，再使用 f-Strings 以及 `format()` 方法將大流行全球現況以維基百科頁面的格式印出為一段敘述文字。
