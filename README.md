# KK 平台开发者指南

> 面向网易 **KK 平台 + Y3 编辑器** 的开发者自学手册 —— 目标是帮你从零做出一款能上线的小游戏。

## 这是什么

本仓库是一份**结构化的本地开发笔记**，把 Y3 编辑器官方文档的要点、开发工作流与实战经验汇总到一处。
省去你在零散的官方文档页之间来回跳转，可以照着学习路径一路读下去。

> 官方文档：`https://163.com/y3/docs` · 本仓库内容由官方公开资料整理，仅供学习。

## 我该从哪看起

- **完全新手** → 先读 [`docs/y3-editor-overview.md`](docs/y3-editor-overview.md) 建立全局认知，再按 [`docs/README.md`](docs/README.md) 的学习路径一步步来。
- **想做出第一个能玩的 Demo** → 走学习路径的「入门」与「实战 Demo」段。
- **想写复杂逻辑** → 直奔「Lua 脚本」段（学习路径第 4 阶段）。
- **想上架赚钱** → 看最后的「发布与运营」段。

## 文档目录

所有笔记在 [`docs/`](docs/) 下，**索引与推荐阅读顺序**见：

👉 **[docs/README.md](docs/README.md)**

## 仓库结构

```
kk-platform-developer/
├── README.md                 # 你在这里：项目入口
├── docs/
│   ├── README.md             # 文档索引 + 学习路径（先看这个）
│   └── y3-editor-overview.md # Y3 编辑器总览
└── (规划中) examples/        # Lua 片段 / 触发器示例 / 数值表模板
```

## 关键链接

| 资源 | 地址 |
|------|------|
| Y3 编辑器下载 | https://163.com/y3/ |
| 开发者文档（内容来源） | https://163.com/y3/docs |
| 开发者学院（视频教程） | https://163.com/learn |
| KK 开发者平台（作者之家） | https://create.kkdzpt.com |
| 交流论坛 | https://163.com/y3/forum |

## 说明

- 仓库内容整理自官方公开文档，版权归原作者所有，本仓库仅作个人学习笔记。
- 文档持续更新中，部分章节为 TODO，见 [`docs/README.md`](docs/README.md) 的状态标记。
