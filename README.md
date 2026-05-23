# cicada-skills

> Agent Skills 集合，专注于深度研究与内容创作。

本仓库收录由 **cicada** 编写或优化的 Agent Skill，基于 [khazix-skills](https://github.com/KKKKhazix/khazix-skills) 框架开发。目标是让 AI 在系统性研究和高质量内容创作任务上达到可用、有性格、不糊弄的标准。

---

## 技能一览

### [hv-struct-analysis · 横纵分析法深度研究](./hv-struct-analysis)

**研究产品 / 公司 / 概念 / 人物时的首选技能。**

核心是双轴分析：纵轴追踪从诞生到当下的完整生命历程（叙事故事呈现），横轴在当下时间截面上与竞品 / 同类进行系统性横向对比，最后交叉两条轴产出独到洞察。最终交付一份排版精美的 PDF 报告（10,000–30,000 字）。

```
触发词：深度研究、系统性梳理、纵横分析、竞品分析、调研一下
输出：PDF 研究报告
```

**方法论溯源**：由数字生命卡兹克（Khazix）提出，经 cicada 修改。融合索绪尔的历时-共时分析、社会科学纵向-横截面研究设计、商学院案例研究法与竞争战略分析。核心原则：纵向追时间深度，横向追同期广度，最终交汇出判断。

---

## 设计哲学

- **触发信号是请求的性质，而非具体用词**：用户期望全面调研就触发深度研究，不是因为说了特定关键词
- **Skill = 哲学 + 技术事实，不是操作手册**：讲清 tradeoff 让 AI 自己选
- **输出有下限**：写 10,000 字报告不是凑字数，方法论到位才能出真洞见

---

## 安装

所有技能遵循 SKILL.md 开放规范，可用于 Claude Code、Codex、OpenCode、OpenClaw 等支持 Skill 的 Agent：

```bash
# 方式一：让 Agent 自动安装
帮我安装这个 skill：https://github.com/lijianaiml/cicada-skills/tree/main/hv-struct-analysis

# 方式二：手动克隆到技能目录
git clone https://github.com/lijianaiml/cicada-skills.git ~/.claude/skills/cicada-skills
```

---

## 目录结构

```
cicada-skills/
├── hv-struct-analysis/           # 横纵分析法深度研究
│   ├── SKILL.md                   # 技能定义文件
│   ├── scripts/
│   │   └── md_to_pdf.py          # Markdown → PDF 转换脚本
│   └── references/
│       └── schema.json           # 技能配置 schema
├── LICENSE
└── README.md
```

---

## 后续计划

更多技能陆续添加中：

- 内容创作类技能
- 知识整理类技能
- 资讯获取类技能

---

## 相关链接

- 原始框架：[khazix-skills](https://github.com/KKKKhazix/khazix-skills) by Khazix
- 方法论讲解：公众号「数字生命卡兹克」

---

## License

MIT