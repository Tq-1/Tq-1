# Tq-1 Skills Lab

<p align="center">
  <strong>把经验写成流程，把流程做成可复用、可测试的 Agent Skills。</strong><br>
  Building open, practical, and testable skills for AI agents.
</p>

<p align="center">
  <img alt="Agent Skills" src="https://img.shields.io/badge/Focus-Agent%20Skills-111827">
  <img alt="Open Source" src="https://img.shields.io/badge/Open%20Source-MIT-2ea44f">
  <img alt="Languages" src="https://img.shields.io/badge/Docs-中文%20%7C%20English-0969da">
</p>

---

## 我在做什么

我正在建设一个 **一仓库一 Skill** 的开源专栏：把科研、编程、调研、日常工作与个人兴趣中的有效方法，封装成 AI Agent 可以稳定复用的工作流。

这里的 Skill 不只是提示词。每个正式项目都会尽量包含：

- 清晰的使用场景与触发边界；
- 可重复执行的步骤、质量门槛与失败处理；
- 完整的 `SKILL.md`、中英文文档与真实示例；
- 可复用模板、脚本或参考资料；
- 自动化验证、测试或评测用例；
- 对主流 Agent / Skill 生态友好的安装结构。

## 最新发布

### [N.L.C. — Never Lose Context](https://github.com/Tq-1/never-lose-context-skill)

> 聊天会忘，项目不该忘。

一个跨会话、跨模型、跨上下文窗口的可验证连续性 Skill。它会保存已核实进展、关键决定、失败尝试、开放问题和第一个可执行动作，并在新 Agent 继续工作前检查 Git、关键文件哈希、交接来源与敏感信息。

`捕获事实 → 记录决定 → 保存失败尝试 → 创建检查点 → 生成交接包 → 检查过期状态 → 安全恢复`

项目包含 `small / standard / deep` 三档上下文预算、`ready / review / reconcile` 恢复门槛、零依赖 Python CLI、秘密扫描与显式脱敏、跨领域适配协议、机器可读评测、单元测试，以及 Claude / Codex / Agent Skills 兼容结构。

## Skill 设计原则

```text
Useful over flashy.        实用优先于炫技
Evidence over confidence.  证据优先于语气
Workflow over prompt.      流程优先于单段提示词
Tests over claims.         测试优先于自我宣称
Portable by default.       默认考虑跨平台复用
```

## 专栏方向

- **通用能力**：研究、决策、写作、规划、验证与信息整理；
- **科研工作流**：论文阅读、文献综述、实验分析与研究复现；
- **开发者工具**：代码理解、调试、测试、评审与交付；
- **日常效率**：会议、知识管理、个人项目与兴趣工作流。

## 已发布 Skills

| # | Skill | 解决的问题 | 状态 |
|---:|---|---|---|
| 01 | [T.E.S.T.](https://github.com/Tq-1/test) | 证据优先的调研、核验、比较与决策简报 | `v1.0.0` |
| 02 | [N.L.C.](https://github.com/Tq-1/never-lose-context-skill) | 跨会话、跨模型的上下文保存、过期检测与安全恢复 | `v1.0.0` |

后续发布的 Skill 将继续补充到这里，不再展示与本专栏无关的旧项目。

---

<p align="center">
  <strong>Follow the repositories to watch this Skill collection grow.</strong>
</p>
