# lhg-skills

刘洪光出品的中文 AI Agent Skills，全开源（MIT），平台中立 Markdown，Claude Code / Codex / 豆包智能体 / Workbuddy / 扣子 / Trae 都能用。

安装任意一个：

```bash
npx skills add lhg-skills/<skill 名>
```

## English

**lhg-skills** publishes 10 open-source (MIT), Chinese-first AI agent skills by Liu Hongguang, a creator based in Hefei, China. The matrix covers the full content-and-engineering loop: Chinese writing with style fingerprinting and AI-flavor diagnosis, deep research dossiers, competitor teardown and topic mining for creators, 30-day cross-platform trend scans, single-file HTML slide generation, an internet data-access layer, AI programming discipline, scientific debugging, security audit, and a quality gate for vetting third-party skills before installing them.

Every skill is plain process Markdown — no dependency on any agent platform — and installs with one command: `npx skills add lhg-skills/<name>`.

## Skill 矩阵（10 个）

| Skill | 名称 | 一句话 |
|---|---|---|
| [`lhg-writing`](https://github.com/lhg-skills/lhg-writing) | 中文写作 | 风格指纹 → Orwell 六规则 → AI 味诊断，写出有人味的中文 |
| [`lhg-slides`](https://github.com/lhg-skills/lhg-slides) | HTML 演示文稿 | 大纲/文档一键生成可编辑的单文件 HTML slides |
| [`lhg-trend`](https://github.com/lhg-skills/lhg-trend) | 近30天热点扫描 | 话题火不火、为什么火、还能不能追 |
| [`lhg-deep-research`](https://github.com/lhg-skills/lhg-deep-research) | 深度调研 | 多源检索 → 结构化中文调研报告 |
| [`lhg-benchmark-topic-factory`](https://github.com/lhg-skills/lhg-benchmark-topic-factory) | 对标拆解选题工厂 | 找对标 → 逆向 100 条选题库 → 口播文案 |
| [`lhg-net`](https://github.com/lhg-skills/lhg-net) | 互联网能力层 | 中文优先多平台取数，取不到诚实说 |
| [`lhg-craft`](https://github.com/lhg-skills/lhg-craft) | AI 编程工程规范 | 分级澄清 → TDD → 独立评审 → 证据门禁 |
| [`lhg-debug`](https://github.com/lhg-skills/lhg-debug) | 系统化调试 | 复现 → 定位 → 修复 → 验证 |
| [`lhg-secure`](https://github.com/lhg-skills/lhg-secure) | 代码安全审计 | 九维度扫描 + 对抗验证，分级风险清单 |
| [`lhg-finder`](https://github.com/lhg-skills/lhg-finder) | 找 skill 质检门 | 装第三方 skill 前的 blocker 检查 + 六维评分 |

## 按场景选

- **做自媒体内容**：lhg-trend 找热点 → lhg-benchmark-topic-factory 拆对标出选题 → lhg-writing 写稿 → lhg-slides 做演示
- **调研一个新领域**：lhg-deep-research 出结构化调研报告
- **写代码做工程**：lhg-craft 定规范 → lhg-debug 修 bug → lhg-secure 做安全审计
- **给 AI 装技能**：lhg-net 提供联网取数能力，lhg-finder 在装第三方 skill 前把质量关

## 常见问题

**Q：这些 skill 免费吗？**
全部免费开源，MIT 协议，可商用（保留署名）。

**Q：怎么安装？**
`npx skills add lhg-skills/<skill 名>`，或直接 clone 仓库把 `SKILL.md` 放进对应平台的 skills 目录。

**Q：支持哪些 AI 平台？**
全部是平台中立的纯 Markdown 流程描述：Claude Code、Codex、豆包智能体、Workbuddy、扣子、Trae 等支持 Markdown 指令的环境都可用。

**Q：质量怎么保证？**
每个 skill 都是纯流程 Markdown、不依赖特定平台、取不到的数据诚实标注；装第三方 skill 前可以用 lhg-finder 做 blocker 检查 + 六维评分。

## 出品

本组织由真人出镜 IP「刘洪光」（安徽合肥）出品。

- 视频号：搜「刘洪光实名上网」
- 微信：lhgsmsw
