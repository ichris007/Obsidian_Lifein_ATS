# Obsidian_Lifein_ATS
Lifein ATS 是一个完全本地化的招聘管理系统，基于 Obsidian 笔记应用构建。无需服务器，所有数据存储在本地，满足隐私安全要求的同时提供强大的招聘全流程管理能力。

[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey.svg)]()

![](https://github.com/ichris007/Obsidian_Lifein_ATS/blob/main/demo/Lifein_ATS_Dashboard.gif)

## 2 核心功能

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

## 3 核心特点

| 特点 | 说明 |
|------|------|
| **零服务器依赖** | 基于 Obsidian 本地文件系统，无需搭建服务器 |
| **隐私安全** | 敏感招聘信息完全本地存储，不上云端 |
| **高度灵活** | 基于 Markdown，可自由定制模板、字段、工作流 |
| **可视化强** | 内置 React 组件，图表、交互看板、动态筛选 |
| **自动化高** | 一键创建文件、自动重命名、自动分类、自动关联 |

---

## 4 系统架构

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

## 5 依赖插件

Lifein ATS 依赖以下 Obsidian 插件：

- **Datacore** - 数据库与可视化核心
- **Dataview** - 数据查询与展示
- **Meta Edit** - 属性编辑
- **QuickAdd** - 快速操作模板
- **Templater** - 模板引擎
- **Tasks** - 任务管理

---
## 6 联系方式

- 作者：科叔
<details>
<summary>扫描二维码联系</summary>
  
<img src="https://github.com/ichris007/ichris007/blob/main/images/Chris_WeChat.jpg" width="300">

</details>

- 项目地址：https://github.com/ichris007/Obsidian_Lifein_ATS
