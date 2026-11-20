# AI Skills

## 接力棒 · 项目共创与交接

[接力棒（jielibang）](skills/jielibang/SKILL.md) 把项目讨论、方案调整、规划执行、验证和跨对话交接放在同一个技能入口里。

**讨论想法 → 发散与比较 → 收敛方案 → 规划 → 执行与验证 → 保存与接棒**

- 根据当前请求继续讨论、规划或执行。
- 区分已采纳的决定、用户倾向、代理建议与待验证假设。
- 通过项目总览与 Handoff.md 保存目标、进度、决策和下次接续位置。
- 支持只讨论、只读检查和按既有授权继续实施。

### 文件

```text
skills/jielibang/
├── SKILL.md
├── agents/openai.yaml
├── assets/AGENTS.template.md
├── assets/Handoff.template.md
└── THIRD_PARTY_NOTICES.md
```

### 使用示例

在支持本地 skills 的 Codex 环境中使用该技能；仓库内技能路径为 `skills/jielibang`。

> $jielibang，先和我讨论这个项目，帮我探索几个方向，暂时不实现。

> 就按这个方案做，并保存进度。

> 接力棒，接着上次的讨论。

技能使用项目内的记录接续工作。没有项目目录或用户要求不写文件时，可以只在聊天中整理。

### 来源

共创结构参考 [obra/superpowers](https://github.com/obra/superpowers) 的 brainstorming 流程并作了整合改写。固定版本和上游 MIT 版权许可见 [第三方作品声明](skills/jielibang/THIRD_PARTY_NOTICES.md)。
