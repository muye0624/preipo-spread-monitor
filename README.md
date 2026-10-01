# Pre-IPO 跨平台价差监控(静态站点)

只读、纯静态页面:`index.html` 轮询同目录的 `data.json`,在浏览器内计算跨平台估值价差并弹窗提醒。
`data.json` 由后台脚本每 ~5 分钟推送(来源:preipo.polyos.ai 公开快照、Hyperliquid 公开 Info API、Binance 第三方聚合价 TradingView/CoinGecko)。

- 价差 ≠ 可无风险套利,非投资建议。
- 仓库内不含任何凭据。
