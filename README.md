# Obsidian Lifein ATS
**Lifein ATS** 是一套构建于 Obsidian、完全本地化的知识驱动型候选人管理系统。

它依托 [Lifein](https://github.com/ichris007/Obsidian_Lifein) 人生管理架构，将传统招聘流程与知识管理理念深度融合，通过双向链接、动态查询、自动化模板与数据可视化能力，**打破信息孤岛，帮助猎头与招聘HR实现候选人资产沉淀与关系网络的长期复利。** 

不同于传统ATS的线性流程逻辑，Lifein ATS 将“企业—职位—人才—流程”整合为统一的数据结构与关系网络，使信息可关联、可追溯、可扩展，实现招聘全周期的系统化管理。

这是一套**高度模块化、强关联、可自动化、可自由定制**的招聘操作系统，使招聘不再只是流程执行，而成为可沉淀、可连接、可持续复利的人才资产经营行为。

>Lifein ATS —— 让招聘数据，成为可复利的人才资产。


[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey.svg)]()

系统首页👇

![](https://github.com/ichris007/Obsidian_Lifein_ATS/blob/main/demo/Lifein_ATS_Dashboard.gif)

## 1 核心特点

| 特点 | 说明 |
|------|------|
| **零服务器依赖** | 基于 Obsidian 本地文件系统，无需搭建服务器 |
| **隐私安全** | 敏感招聘信息完全本地存储，不上云端 |
| **高度灵活** | 基于 Markdown，可自由定制模板、字段、工作流 |
| **可视化强** | 内置 React 组件，图表、交互看板、动态筛选 |
| **自动化高** | 一键创建文件、自动重命名、自动分类、自动关联 |

---

## 2 主要功能

### 2.1 👥 候选人管理
- 完整候选人资料库（个人信息、工作经历、教育背景、联系方式）
- 多维度人才池检索（公司、职位、地区、学校、学历、行业、专长）
- 候选人状态分类与标记
- 重要程度星级评级

<details>
<summary>点击查看演示</summary>
  
#### 人才管理

![](https://github.com/ichris007/Obsidian_Lifein_ATS/blob/main/demo/Lifein_ATS_Talents.gif) 

#### 人才库检索

![](https://github.com/ichris007/Obsidian_Lifein_ATS/blob/main/demo/Lifein_ATS_Talents_pool.gif)
</details>

### 2.2 📋 职位/项目管理
- 猎头项目全生命周期管理
- 项目状态追踪：预搜索 → 进行中 → 已暂停 → 已停止 → 已完成
- 招聘进度可视化
- 截止日期提醒与优先级排序

<details>
<summary>点击查看演示</summary>
  
![](https://github.com/ichris007/Obsidian_Lifein_ATS/blob/main/demo/Lifein_ATS_Project.gif)
</details>

### 2.3 🏢 客户与联系人管理
- 企业客户资料库
- 客户开发状态追踪
- 客户联系人独立管理
- 自动关联项目与会议记录

<details>
<summary>点击查看演示</summary>

#### 客户/企业管理
![](https://github.com/ichris007/Obsidian_Lifein_ATS/blob/main/demo/Lifein_ATS_Company.gif)

#### 客户/企业联系人管理
![](https://github.com/ichris007/Obsidian_Lifein_ATS/blob/main/demo/Lifein_ATS_Contacts.gif)
</details>

### 2.4 🔄 候选人跟进追踪
- **16阶段招聘流程**：从潜在人选到已入职的全流程管理
  - 推荐前：潜在人选、初步沟通、顾问评估
  - 招聘中：推荐简历、简历初筛、一面~三面、HR面、谈Offer、待入职、已入职
  - 负反馈：简历淘汰、面试淘汰、人选放弃、客户放弃
- 匹配度与意愿度评估
- Offer 状态追踪
- 节点记录功能

<details>
<summary>点击查看演示</summary>

#### 候选人追踪面版
![](https://github.com/ichris007/Obsidian_Lifein_ATS/blob/main/demo/Lifein_ATS_Applications_1.gif)

#### 候选人追踪详情
![](https://github.com/ichris007/Obsidian_Lifein_ATS/blob/main/demo/Lifein_ATS_Applications.gif)
</details>

### 2.5 📊 可视化仪表板
- **招聘阶段统计图**：周/月/季/年度多维度统计
- **招聘趋势图**：时间维度趋势分析
- **Pipeline 看板**：按流程阶段分组查看
- 实时数据悬停显示

<details>
<summary>点击查看演示</summary>
  
![](https://github.com/ichris007/Obsidian_Lifein_ATS/blob/main/demo/Lifein_ATS_Process_stats_1.gif)
![](https://github.com/ichris007/Obsidian_Lifein_ATS/blob/main/demo/Lifein_ATS_Process_stats_2.gif)
</details>

### 2.6 🔗 智能数据关联
- 项目 ↔ 候选人追踪 ↔ 人才 ↔ 客户 ↔ 联系人 全链路关联
- 自动反向链接与引用
- 任务与日记自动关联

---


## 3 系统架构

```
Lifein_ATS/
├── 01Projects/猎头/          # 企业资料、职位/项目
├── 07People/
│   ├── Talents/              # 人才库
│   ├── Client_Contacts/      # 客户联系人
│   └── Applications/         # 候选人追踪
├── 08Bases/ATS.base          # 数据库配置
├── Settings/ATS_modules/     # 功能模块
└── Templates/                # 模板文件
```

---

## 4 依赖插件

### 4.1 核心功能依赖（**必须**）：
- **Datacore** 数据库与可视化核心
- **Dataview** 数据查询与展示
- **Meta Edit** 属性编辑
- **QuickAdd** 快速操作模板
- **Templater** 模板引擎
- **Tasks** 任务管理
- **Update frontmatter modified date** 自动更新属性

### 4.2 重要依赖（非必须）：
- **Pretty Properties** 实现任务进度
- **Various Complements** 多类型内容补全

### 4.3 其它（建议）：
- Number Headings 标题自动编号
- Omnisearch 全局极速搜索
- Editing Toolbar 编辑快捷工具栏
- Floating Headings 标题悬浮固定
- Force note view mode 强制笔记视图
- Reminder 笔记提醒定时
- Word Splitting for Simplified Chinese in Edit Mode and Vim Mode 中文分词优化

---
## 5 联系方式

- 作者：科叔
<details>
<summary>微信扫描二维码联系</summary>
  
<img src="https://github.com/ichris007/ichris007/blob/main/images/Chris_WeChat.jpg" width="300">

</details>

- 项目地址：https://github.com/ichris007/Obsidian_Lifein_ATS
