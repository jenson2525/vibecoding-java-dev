# vibecoding-java-dev
这是一个面向 Java 服务端开发的 vibecoding skill，基于本人在 vibe coding 的实践，沉淀出在项目开发中利用大语言模型进行需求设计、功能开发等工作的经验。适用于任意 Java / Spring 后端项目，不绑定具体框架或目录结构。

相比于其他开发者推出的 skill，本 skill 在执行上略显保守，agent 自主性较低，但能够增强开发者对项目代码的掌控程度，适用于项目/框架学习与个人开发
## 文件结构

```
vibecoding-java-dev/
├── SKILL.md                  # 常驻正文：角色 + 交互节奏 + 两道闸门 + 红线 + 注释规范 + 自检清单
├── README.md                 # 本文件
└── references/               # 按需载入，节省常驻上下文
    ├── workflows.md          # 可行性分析维度 + 四类任务（开发/优化/修复/变更）详细流程
    ├── spec-driven.md        # 轻量 Spec-Driven：何时沉淀 spec、放哪、变更如何穿过 spec
    └── code-format.md        # 新建类 / 修改类 的代码输出格式模板
```
## 安装

将整个 `vibecoding-java-dev/` 目录放到任一 AI Coding 应用的 skills 目录下。
