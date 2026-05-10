# quant-framework

统一量化回测框架 — Config-driven backtesting engine

## 架构

```
quant_framework/
├── core/engine.py       # 统一回测引擎（单一 run() 入口）
├── data/loader.py       # 统一数据加载（Qlib Parquet + scores.parquet）
├── signals/chan.py      # 缠论信号检测器（placeholder）
├── environment/classifier.py  # 环境分类器（MA/ER/None）
├── risk/manager.py      # 风险管理器
├── output/reporter.py   # 结果报告器
├── config/config.py     # 配置管理（dataclass + YAML）
└── README.md
```
