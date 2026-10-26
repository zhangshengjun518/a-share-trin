# A 股市场广度 / TRIN 跟踪

首次运行后，本页会被自动替换为最新数据表和图表。

## 使用

1. 仓库 **Settings → Secrets and variables → Actions → New repository secret**，名称 `TUSHARE_TOKEN`，值填 tushare token。
2. **Actions → 更新 TRIN 数据 → Run workflow** 手动运行一次（首次从 2024 年拉起，约 30–60 分钟）。之后每个交易日北京时间 18:07 自动运行，只拉新增日期。
3. 运行完成后刷新仓库首页即可看到结果。
