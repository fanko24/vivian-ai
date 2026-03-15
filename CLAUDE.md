# CLAUDE.md

本文件为 Claude Code (claude.ai/code) 在此仓库中工作时提供指导。

## 项目概述

Vivian AI 是专为8岁一年级小女孩设计的AI启蒙课程。内容全部使用中文编写，通过故事、动手实践和创意项目引导孩子认识和使用AI工具。

## 仓库结构

```
vivian-ai/
├── lessons/
│   └── semester-1/           # 第一学期（12周课程）
│       ├── module-1/         # 模块一：认识AI朋友（第1-3课）
│       ├── module-2/         # 模块二：AI创作工坊（第4-8课）
│       └── module-3/         # 模块三：AI学习伙伴（第9-12课）
├── docs/                     # 文档
│   ├── progress.md           # 学习进度追踪
│   ├── safety-guide.md       # 安全使用指南
│   └── faq.md                # 家长常见问题
└── resources/
    ├── tools.md              # 推荐AI工具
    └── glossary.md           # AI词汇表
```

## 课程文件结构

每节课包含6个标准文件：

| 文件 | 用途 |
|------|------|
| `README.md` | 课程概览、学习目标、准备清单 |
| `story.md` | 故事引入，激发孩子兴趣 |
| `content.md` | 知识讲解 |
| `hands-on.md` | 动手实践步骤 |
| `homework.md` | 课后作业 |
| `parent-guide.md` | 家长指导 |

## 写作规范

- **语言**：全部使用简体中文
- **目标读者**：8岁儿童及其家长
- **语气**：亲切友好、鼓励性强、适合儿童理解
- **格式**：适当使用emoji增加趣味性
- **AI工具推荐**：国内工具优先推荐豆包，国际工具优先推荐ChatGPT

## 编辑注意事项

1. 保持与现有课程结构一致
2. 语言要简单易懂，适合8岁孩子
3. 适当加入家长指导内容
4. 新增或修改课程时更新 `docs/progress.md`
5. 动手实践内容需符合 `docs/safety-guide.md` 的安全指南
