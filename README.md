china-wei-quant · 个人量化研究
股票量化研究（A 股为主）：数据获取 → 因子与策略研究 → 回测验证 → 实盘辅助。

仓库导航
仓库	说明
quant-backtest	A 股量化回测框架：策略回测 · 因子研究 · 敏感性分析 · 每日信号 · QMT 实盘桥
常用工具栈
数据：AKShare · AKTools · Tushare
回测/框架：Backtrader · vn.py · Qlib
分析：pandas · numpy · matplotlib · Jupyter
组织约定
每个研究方向一个独立仓库，命名小写加连字符（如 factor-momentum、backtest-lab、data-fetcher）
研究仓库默认 Private，是否公开按仓库单独决定
大体量行情/数据文件不进 git：放本地 data/ 目录，写进 .gitignore
