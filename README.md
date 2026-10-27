# Lab1-01 — My OSS Contribution Plan

> 本文件用于记录我目前对开源项目贡献的想法，以及本学期的课程学习目标。
> 最后更新：2026-10-27

## 1. 关于我 / About Me

| 项目 | 内容 |
| --- | --- |
| 姓名 | 高蕴程 |
| 学号 | 2026111501 |
| GitHub | [@lord654654787](https://github.com/lord654654787) |
| 课程 | 开源软件开发 |
| 专业 / 年级 | 制药工程/26级 |

## 2. 我对开源的理解

开源对我来说不只是「免费使用别人的代码」，而是一个**协作生产软件**的公共空间：

- **代码是公开的**，任何人都可以阅读、复现、修改和分发；
- **协作是有流程的**：Issue 讨论问题 → Pull Request 提交改动 → Review 后合并；
- **许可证（License）决定规则**：MIT / Apache-2.0 / GPL 赋予的权利与义务完全不同；
- **社区也是产出**：文档、教程、翻译、答疑、缺陷复现，和写代码一样是贡献。

## 3. 我目前对开源项目的贡献想法

### 3.1 切入点：先从「低门槛但真实有用」的事情做起

我打算按照由易到难的顺序参与：

1. **文档类贡献**：修正 README 里的错误示例、补充安装步骤、给新手写 Quick Start。
2. **本地化（i18n）**：把中文文档补全或修正，帮助国内用户降低上手成本。
3. **缺陷复现**：在 Issue 里提供最小可复现示例（MCVE）、日志和环境信息，帮维护者省时间。
4. **小修复**：从 `good first issue` / `help wanted` 标签开始，修拼写、边界条件、类型标注、测试用例。
5. **功能开发**：熟悉代码结构后再提功能 PR，先开 Issue 对齐设计，避免白做。

### 3.2 想参与的项目方向

- **Python 生态工具**：CLI 工具、数据处理库（与课程作业技术栈一致，能边学边用）。
- **深度学习 / AI 框架**：模型训练脚本、文档示例、bug 修复。
- **中文社区项目**：文档翻译、术语统一、新手教程。

### 3.3 我对「贡献」的几个原则

- **先沟通再动手**：大改动前先在 Issue 说明方案，尊重维护者的设计取向。
- **小步提交**：一个 PR 只做一件事，方便 Review 和回滚。
- **遵守规范**：读 `CONTRIBUTING.md`、代码风格、提交信息规范（如 Conventional Commits）。
- **有始有终**：PR 被要求修改就及时回应，不被合并也把原因记录下来。
- **不做 「刷贡献」**：不为凑 commit 数去改空格、改无意义文案。

### 3.4 长期想法

希望一个学期之后，我能从「只会用开源」变成「能稳定给开源交付东西」的人：
持续维护一两个自己发起的小工具，同时在 1–2 个活跃社区里长期做 Issue 答疑和代码审查。

## 4. 本学期的课程学习目标

### 4.1 知识目标

- 掌握 Git / GitHub 的核心工作流：`clone`、`branch`、`commit`、`push`、`Pull Request`、`Review`、`merge`。
- 理解开源许可证（MIT / Apache-2.0 / GPL-3.0）的差异，能为自己的项目选择合适许可证。
- 能读懂一个陌生项目的目录结构、构建方式与测试方式。

### 4.2 能力目标（SMART）

| 编号 | 目标 | 衡量标准 |
| --- | --- | --- |
| G1 | 完成环境与工具链搭建 | 本机 Git 可用，GitHub 账号完成认证，能成功 clone / push |
| G2 | 完整走通一次贡献流程 | 至少提交 1 个被合并的 Pull Request（文档类也算） |
| G3 | 参与社区讨论 | 本学期至少发 3 条有价值的 Issue（含复现信息）或 Review 意见 |
| G4 | 建立个人开源项目 | 自己发起 1 个仓库：README、LICENSE、Issue 模板齐全 |
| G5 | 形成可复用的笔记 | 一份「开源贡献流程与踩坑记录」文档，能直接给下届同学用 |

### 4.3 时间安排

| 阶段 | 时间 | 主要任务 |
| --- | --- | --- |
| 第 1–2 周 | 环境与基础 | 装 Git、配置身份与认证、熟悉 commit / push 流程 |
| 第 3–4 周 | 读代码 | 选 2 个候选项目，读 CONTRIBUTING 与目录结构，跑通本地测试 |
| 第 5–8 周 | 首次贡献 | 从 good first issue 入手，提交首个 PR 并跟进 Review |
| 第 9–12 周 | 深入参与 | 参与 Issue 讨论、做代码审查、尝试修一个非简单的 bug |
| 第 13–16 周 | 总结 | 整理贡献记录、写课程报告、完善个人项目 |

## 5. 参考资源

- [Git 官方文档](https://git-scm.com/doc)
- [GitHub Docs — Hello World](https://docs.github.com/get-started/quickstart/hello-world)
- [How to Contribute to Open Source](https://opensource.guide/how-to-contribute/)
- [First Contributions](https://github.com/firstcontributions/first-contributions)
- [Choose a License](https://choosealicense.com/)
