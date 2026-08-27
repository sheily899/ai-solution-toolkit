# 评测与追踪

## Promptfoo

- 官网：https://www.promptfoo.dev/
- 文档：https://www.promptfoo.dev/docs/intro/
- 开源仓库：https://github.com/promptfoo/promptfoo
- 用途：批量评测提示词、模型、RAG 与 Agent，并支持安全测试。
- 计划实践：为 AskData 增加正常查询、歧义澄清、越权、执行失败和提示注入测试。
- 状态：待体验

## 评测原则

采用证据驱动迭代：

> Baseline → Evaluation → Error Analysis → Hypothesis → Minimal Fix → Regression → Evaluation

最低要求：

- 明确数据集和测试范围；
- 保存失败 Case 与运行 Trace；
- 区分检索、生成、安全和执行错误；
- 修复失败 Case，同时防止成功 Case 回归；
- 全量复测后再下结论。
