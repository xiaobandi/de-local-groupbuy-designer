# 核销数据复盘调价

> 核销数据 → 识别滞销款 → 调价/换品建议

工作流 `wf-local-groupbuy-redemption-review`　·　归属 团购引流设计师　·　触发 定时（每月）　·　
复杂度 M　·　阶段 P2

## 调用链

- `数据对接`（data-ingest-adapter）
- `定价测算器`（pricing-calculator）

## 文档

- [`WORKFLOW.md`](WORKFLOW.md) — 完整编排、闸门、降级与验收标准
- [`tests/cases.yaml`](tests/cases.yaml) — 端到端 / 闸门 / 降级用例

## 一句话试用

```text
帮我跑 团购引流设计师 的「核销数据复盘调价」：<你的输入>
```
