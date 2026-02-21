# 🔨 ContentForge / 内容锻造厂

**帮你做出读者忍不住分享的内容**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/szj2ys/content-forge/pulls)

---

## 这个项目解决什么问题？

你写的内容正确但无聊。完整但没记忆点。发出去之后阅读量平平，评论区安静。

问题不在于你写得不够努力，而在于你没有一把尺子来衡量"好"。

ContentForge 给你这把尺子：**5条不平庸标准 + 4步生产闭环 + 实战模板**。

---

## 什么是"不平庸"的内容？

| # | 标准 | 一句话检验 |
|---|------|-----------|
| 1 | **有信息增量** | 读者读完学到了什么之前不知道的？ |
| 2 | **有反直觉观点** | 有没有一个观点让读者说"原来不是我以为的那样"？ |
| 3 | **有真实证据** | 核心观点有具体案例或数据支撑吗？ |
| 4 | **读完能行动** | 读者知道下一步该做什么吗？ |
| 5 | **有分享冲动** | 读者想推荐给谁？ |

👉 [完整标准 + 自检评分卡](methodology/00-not-mediocre.md)

---

## 4 步闭环

```
选题 Discover → 创作 Create → 审核 Review → 发布 Ship
      ↑                                          |
      └──────────── 复盘反馈 ─────────────────────┘
```

1. **选题** — 用评分卡和用户需求挖掘指南找到值得做的题目 → [方法论](methodology/01-discover.md)
2. **创作** — 先骨架后血肉，用结构化方法高效产出 → [方法论](methodology/02-create.md)
3. **审核** — 用检查清单和不平庸标准确保质量 → [方法论](methodology/03-review.md)
4. **发布** — 发布+72小时跟踪+复盘闭环 → [方法论](methodology/04-ship.md)

---

## 看看实际效果

> "用选题评分卡评估了5个候选，选定得分最高的一个，用四遍修改清单改稿。总耗时4小时（比平时多1小时），但完成率从45%提升到68%。"
> — [案例：用 ContentForge 写一篇技术文章](examples/article-example.md)

> 更多案例：[课程设计案例](examples/course-example.md)

---

## 快速开始

1. `git clone https://github.com/szj2ys/content-forge.git`
2. 读 [不平庸的5条标准](methodology/00-not-mediocre.md)（5分钟）
3. 用 [选题调研模板](templates/article/01-topic-research.md) 评估你的候选选题（10分钟）
4. 选定选题，用 [大纲模板](templates/article/02-outline.md) 搭骨架（5分钟）
5. 写初稿，用 [审核检查清单](checklists/review-checklist.md) 自检
6. 发布，用 [发布检查清单](checklists/ship-checklist.md) 复盘

---

## 项目结构

```
content-forge/
├── methodology/                 # 方法论（为什么这样做）
│   ├── 00-not-mediocre.md      # ⭐ 不平庸内容的5条标准
│   ├── 01-discover.md          # 选题方法论（含用户需求挖掘指南）
│   ├── 02-create.md            # 创作方法论
│   ├── 03-review.md            # 审核方法论
│   ├── 04-ship.md              # 发布方法论（含数据驱动验证）
│   └── 05-ai-assisted.md       # AI 辅助写作指南
├── templates/                   # 实战模板
│   ├── article/                # 文章模板（4个）
│   ├── course/                 # 课程模板（3个）
│   └── book/                   # 书籍全流程工作表
├── checklists/                  # 检查清单（4个）
└── examples/                    # 真实案例
```

---

## 谁适合用？

- 写文章但阅读量平平的博主
- 做课程但完课率不高的讲师
- 想出书但不知从何下手的作者
- 想提升内容质量但缺少标准的团队

---

## 方法论来源

- [得到品控手册](https://www.dedao.cn/) — 选题评估、品控标准、交付规范
- 内容营销最佳实践 — 受众调研、效果度量
- 敏捷开发 — 迭代交付、MVP、快速反馈

---

## 贡献

欢迎 PR。特别欢迎：真实案例、新内容形式的模板、方法论改进。

## License

[MIT](LICENSE)
