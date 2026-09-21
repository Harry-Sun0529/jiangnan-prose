# jiangnan-prose

从江南《龙与少年游》全书 13.9 万字逐句蒸馏出的中文随笔写作技能，供 Claude Code 使用。只提炼可复用的手艺（节奏、结构、语域、情绪处理），不复用原书专名与整句签名表达。

## 安装

```bash
git clone https://github.com/Harry-Sun0529/jiangnan-prose.git
ln -s "$(pwd)/jiangnan-prose" ~/.claude/skills/jiangnan-prose
```

## 使用

在 Claude Code 中输入 `/jiangnan-prose`，附上素材或要求即可。两种模式：

- **创作**：给素材或提纲，按江南式随笔成文（叙事回忆体 / 影评体 / 序跋体 / 抒情短文）。
- **修订**：贴已有文字，先诊断病灶、最小干预。内置防「用力过猛」机制，不会为凑规则给文字硬加装置。

## 说明

`SKILL.md` 为完整规则层，独立可用。更深的原文证据分析（`references/`）因含原书引文，不随本仓库分发，仅本地保留。
