# 投資組合最佳化 (Portfolio Optimization)

以**凸優化 (convex optimization)** 對美股投資組合做均值–變異數最佳化（Markowitz），並比較不同年度的權重與績效。

## 內容
| 檔案 | 說明 |
|------|------|
| `log_return_final.ipynb` | 以 `yfinance` 抓取 10 檔美股（MSFT, AAPL, AMZN, META, GOOGL, GOOG, JNJ, BRK-B, V, JPM）2022–2024 資料，計算 log return 與 Sharpe ratio，使用 `cvxpy` 求最適權重，並以 GBM 模擬路徑 |

## 執行
```bash
pip install yfinance pandas numpy cvxpy matplotlib
```
直接執行 notebook；資料由 `yfinance` 線上抓取，無需附帶資料檔。
