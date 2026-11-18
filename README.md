# Find Skills CN

**用中文说需求，找到适合的 Agent Skill。**

## 功能与流程

理解任务、先看技能榜、按关键词检索、核对安装量与来源、给出命令和链接、在用户愿意时安装；没有合适结果时如实提供替代路径。上游技能正文保留。

## 只补三个细节

- 把中文任务映射为具体英文检索词，补少量常见同义表达。
- 中文说明匹配原因，技能名与安装命令不翻译。
- 明确“找技能”与“安装技能”的区别，安装量和仓库 Star 分开标注，未知数据不补造。

## 安装与调用

```bash
npx skills add batespaige357-tech/find-skills-cn --skill find-skills-cn
```

对助手说“用 find-skills-cn 帮我找适合当前任务的技能”，或在 Codex 中使用 `$find-skills-cn`。也可将 `skills/find-skills-cn` 整个目录放进助手支持的技能目录。需要支持 Agent Skills 的助手；执行 Skills CLI 时需要可用的 Node.js/npm 和网络，不附带 CLI 实现。

## 来源与许可

基于 [vercel-labs/skills 的 find-skills](https://github.com/vercel-labs/skills/tree/main/skills/find-skills)，由本仓库维护。

MIT，保留 Vercel, Inc. 版权和完整许可证。没有复制上游演示或效果截图，没有声称官方关联。具体参考版本与验证边界见 [CHANGES.md](CHANGES.md)。
