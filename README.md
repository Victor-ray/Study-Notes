# Study-Notes

个人学习笔记与实用资料库，收集经验手册、复习资料和操作方法，也作为个人 GitHub 仓库的分类导航入口。

<!-- personal-organization:start -->
## 个人仓库导航

按日常用途整理，方便查找资料、继续项目和维护工具。

| 分类 | 仓库 | 主要内容 / 维护入口 |
| --- | --- | --- |
| 个人资料 | [Study-Notes](https://github.com/Victor-ray/Study-Notes) | 学习笔记、经验手册与复习资料；现有资料见下方导航 |
| 自己开发与学习的项目 | [Agent_Project_OnCall](https://github.com/Victor-ray/Agent_Project_OnCall) | SuperBizAgent：Java / Spring Boot、RAG 问答与 Agent 运维 |
| 自己开发与学习的项目 | [AI-coding](https://github.com/Victor-ray/AI-coding) | AI 编程实践；目前主要为 `Game/` 下的 Godot 卡牌游戏《狱火爬升》 |
| 自用工具与工作流 | [skills](https://github.com/Victor-ray/skills) | 个人 Codex Skills；目前为 `lls-csdn` 中文技术科普写作技能 |
| 自用工具与工作流 | [ai-daily-news](https://github.com/Victor-ray/ai-daily-news) | 基于 TrendRadar 的资讯采集与推送；配置和上游来源见仓库说明 |
| 网站与博客 | [Victor-ray.github.io](https://github.com/Victor-ray/Victor-ray.github.io) | Hexo / Butterfly 博客静态部署文件；源码位置待确认 |
| 网站与博客 | [victor-homepage](https://github.com/Victor-ray/victor-homepage) | Vue 3 + Vite 像素主页源码及部署流程 |
| 网站与博客 | [ray-s-home-page](https://github.com/Victor-ray/ray-s-home-page) | 原生 HTML / CSS / JavaScript 主页与媒体素材 |

### 新内容放在哪里

- **能独立运行或部署的项目**：单独建仓库；小实验只有在属于同一个实践集合时才放在已有项目中。
- **零散笔记、手册、复习资料**：归入本仓库，先按主题收纳，有实际内容时再增加目录。
- **可复用的 Skill 与配套资源**：归入 `skills`，每个 Skill 使用独立目录。
- **基于上游的自用工具**：保留来源和许可证，区分个人配置、个人改动与上游代码。
- **网站**：在对应站点源码仓库维护；源码与生成文件分清楚。

本仓库现有秋招手册位于 `career/autumn-recruitment/`；现有 PDF 保留原路径，避免已有链接失效。后续同主题资料优先归入 `career/`。

### 维护约定

- 每个仓库的 README 说明用途、主要入口和维护方式。
- 三个网站分别记录用途；是否继续长期维护，由实际使用情况决定。
- 本次目录与文档整理不代表项目或自动任务已重新运行验收。

仓库分类整理日期：2026-11-13。
<!-- personal-organization:end -->

## 资料导航

| 资料 | 内容 | 格式 |
| --- | --- | --- |
| [秋招准备手册](./career/autumn-recruitment/index.html) | 面向 2028 届的实习与秋招时间线、投递渠道、材料清单和面试复盘 | HTML，离线单文件 |
| [笔试 - AI Coding 技巧](./笔试-aicoding技巧.pdf) | AI 协作编程的解题流程、提示词模板、测试方法与考场检查清单 | PDF，10 页，含 4 张经验原图 |

## 秋招准备手册

面向 2028 届求职者，包含实习与秋招时间线、投递渠道、申请材料清单、千问辅助面试复盘和飞书投递记录表。

- [查看 HTML 文件](./career/autumn-recruitment/index.html)
- [下载手册](https://github.com/Victor-ray/Study-Notes/raw/refs/heads/main/career/autumn-recruitment/index.html)

下载后用浏览器打开即可使用交互功能，无需安装依赖。GitHub 文件页显示源码，暂未提供在线网页预览。招聘时间和工具入口请按实际情况核对。

## 笔试 - AI Coding 技巧

这份资料整合了小红书经验截图与公开测评平台说明，重点面向允许或要求使用 AI 的仓库修改题、工程项目题和限时协作编程题。

核心思路：**先把需求变成验收清单，再让 AI 小步修改；每一步看 Diff、跑测试，最后由自己对结果负责。**

### 内容概览

- AI Coding 的考察重点与平台规则边界；
- 从读题、跑基线到实现、调试、验收、自审的六步流程；
- 60 / 90 分钟考场时间分配；
- 可复制的任务拆解、限定修改、调试、测试与审查提示词；
- 幂等、时间、状态流转、异常路径等高风险测试点；
- 高频踩坑、语言选择、七天训练安排与交卷前检查清单。

### 阅读与分享

- [在线预览 PDF](./笔试-aicoding技巧.pdf)
- [下载 PDF](https://github.com/Victor-ray/Study-Notes/raw/refs/heads/main/%E7%AC%94%E8%AF%95-aicoding%E6%8A%80%E5%B7%A7.pdf)

四张原图已嵌入 PDF，单独转发该文件即可查看，无需额外图片文件夹。如果 GitHub 预览加载失败，可以下载后用浏览器或 PDF 阅读器打开。

建议先通读六步流程，再做一次限时练习；练习后对照测试清单复盘，考前使用最后的检查清单。

## 使用说明

- 这些资料用于个人学习与求职准备，不是企业官方题库，也不保证具体考试成绩。
- 考试允许使用 AI，不代表允许使用任意外部 AI。工具权限、题型与评分标准以当次考试规则为准。
- 截图中的公司范围、语言优势、分数区间和提分个例属于经验性说法，不应当作统一结论；文档已单独说明这些边界。
- 原图内容与整理内容分别归其对应作者所有，不将转载的经验包装为本人原创成果。公开引用时请保留来源说明。

笔试 PDF 资料整理日期：2026-09-30；本 README 仓库导航更新于 2026-11-13。
