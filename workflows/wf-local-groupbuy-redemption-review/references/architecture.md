# 核销数据复盘调价 · 速查

| 项 | 内容 |
|---|---|
| slug | `wf-local-groupbuy-redemption-review` |
| 层级 | L2-workflow |
| 归属 | 团购引流设计师（`de-local-groupbuy-designer`） |
| 复杂度 / 阶段 | M / P2 |
| 能力族 | — |
| 定义出处 | — |
| 复用情况 | — |

## 调用的 SKILL

| 技能 | slug | 来源 |
|---|---|---|
| 数据对接 | `data-ingest-adapter` | 本仓 |
| 定价测算器 | `pricing-calculator` | 本仓 |

## 字段

| 项 | 内容 |
|---|---|
| 必需输入 | 本工作流的起始材料（见 `SKILL.md`「执行步骤」第 1 步）；用户身份与目标平台/渠道 |
| 可选输入 | 历史产出；账号人设；渠道规则；上一周期的数据 |
| 产出 | 调价/换品建议 |
| 脚本 | 无 |
