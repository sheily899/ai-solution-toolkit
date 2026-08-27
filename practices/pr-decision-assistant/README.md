# AI PR Decision Assistant

## 定位

把需求、代码变更和风险提示串成证据链，辅助 Reviewer 聚焦人工审查点，不替代审批。

## 核心链路

Context Resolver → Requirement Interpreter → Change Mapper → Risk Synthesizer → Web UI → Evaluation。

## 当前边界

- 当前为公开 Demo，不代表真实客户上线；
- 需求不足时不应猜测；
- 风险提示需要关联文件、函数或代码证据；
- 高风险和低信度结果转人工复核。

## 下一步

- 补充真实 Reviewer 对照测试；
- 完善证据链覆盖；
- 修复并回归 Web E2E 测试；
- 记录时间、采纳率和失败 Case。
