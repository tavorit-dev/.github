<div align="center">

# Talvori

**让智能，服务于你的每一次选择**

Talvori 正在构建一组面向日常决策的 AI Agent。<br />
不替你做完所有事，只在需要判断的时候，把信息、取舍和下一步放在一起。

[![GitHub](https://img.shields.io/badge/GitHub-tavorit--dev-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/tavorit-dev)
[![Email](https://img.shields.io/badge/Email-talvori%40163.com-2F6BFF?style=flat-square)](mailto:talvori@163.com)
[![X](https://img.shields.io/badge/X-%40windf196796-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/windf196796)

</div>

---

## 我们在做什么

Talvori 关注那些每天都会发生、却很少被认真对待的选择：出门要不要带伞，今天先做哪件事，这次出行怎么安排。我们把分散的信息收拢成一条可执行的建议，把决定权留给你。

- **天气箴言** —— 微信小程序。把「今天会不会下雨」变成「今天该怎么安排」，读取实时气象数据，再结合你的场景给出一句能直接执行的建议。
- **智能助手 SaaS** —— 面向团队，正在打磨中。
- **开源** —— 核心判断逻辑、接口与数据结构会逐步开放，目前已公开四个 Skill 项目（见下方「开源项目」）。

第一批智能服务正在打磨中；已公开的开源项目可以查看，其中可运行的 Skill 可以直接使用。

## 从信息，到行动

每一款 Talvori 产品都会走同一条路径。产品会变，这套路径不变。

1. **理解场景** —— 读取时间、地点、天气与你的偏好，先弄清楚你正处在什么情境里。
2. **形成判断** —— 把多源信息收拢成少数几个选项，并说明每个选项的取舍。
3. **落到行动** —— 输出一句今天就能执行的话：带伞、改期，或先做哪一件。

## 原则

产品会变，原则不变。

- **克制** —— 不为了展示能力而增加功能。每一次提醒，都应该值得打断你。
- **可信** —— 每个建议都尽量说明依据。你可以不同意，也可以自己判断。
- **开放** —— 核心逻辑会逐步开放。工具应该经得起查看，也经得起改进。

## 开源项目

我们把 Talvori 的判断逻辑拆成可复用、可检查的 Skill 开放出来：先看证据，再给建议，输出可校验。

| 项目 | 简介 | 技术 | 许可证 |
| --- | --- | --- | --- |
| [weather-advisor-skill](https://github.com/tavorit-dev/weather-advisor-skill) | 让兼容 Skill 的 Agent 在天气建议上做到「先看证据，再给建议，输出可校验」：入口 Skill + JSON Schema + 6 组示例 + 32 条验收用例 | Markdown / JSON Schema / Python | Apache-2.0 |
| [Gewu-skill](https://github.com/tavorit-dev/Gewu-skill) | 格物：从技术文章中识别真正值得可视化的原理，提取可验证的解释模型（VEM），渲染并验证准确、克制的 SVG 原理图 | Python / SVG | Apache-2.0 |
| [ResearchScout-Skill](https://github.com/tavorit-dev/ResearchScout-Skill) | 研究侦察员：把一个研究主题变成可断点续跑、可追溯的本地知识库，发现来源、合规采集、抽取证据并导出 Markdown / CSV | Python / Markdown | 尚未确定 |
| [WriterSkill](https://github.com/tavorit-dev/WriterSkill) | 天工 · Tiangong：通用写作 Skill。理解创作意图、规划内容结构、在写作过程中给出提示，并规划配图与排版；目前已完成 PRD 与设计文档，Skill 本体设计中 | Markdown | 尚未确定 |

更多开源项目正在整理中。欢迎从 issue 和 pull request 开始参与。

### 天工 · Tiangong

> 辅助创作，而非替代创作。

天工是我们在内容创作方向上的通用写作 Skill。它不以「给一个主题、返回一篇全文」为目标，而是以作者的想法为起点：理解主题、读者与发布场景，规划文章结构，在写作过程中提示该展开什么、缺少哪些论据，最后完成视觉规划与排版。

它支持三种介入方式，用户可以从任意一种开始，也可以反复返回修改：

- **引导创作** —— 只有一个想法，由天工逐步引导完成。
- **协作写作** —— 已有部分草稿，天工分析上下文并给出下一步建议。
- **内容优化** —— 已有成稿，天工直接进入评审、修改与优化。

在能力分工上，天工负责内容组织与创作，格物负责技术原理提取与图解。天工判断文章哪里需要图、需要什么图，格物给出可验证的可视化方案，再由天工整合回文章——两个 Skill 有明确边界，而不是重复实现。

设计文档已公开，Skill 本体仍在设计中。欢迎阅读设计文档，并在 issue 中提出你的场景与建议。

## 联系我们

- 邮箱：[talvori@163.com](mailto:talvori@163.com)
- GitHub：[@tavorit-dev](https://github.com/tavorit-dev)
- X：[@windf196796](https://x.com/windf196796)
- 微信公众号：哈希表

无论是产品建议、合作意向，还是你正在面对的具体场景，都欢迎写信告诉我们。

---

<div align="center"><i>把复杂留给自己，把从容留给人。</i></div>
