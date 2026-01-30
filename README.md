# The Asymmetrical Time（不对称时间）

一个创作项目，用于组织和管理《不对称时间》系列小说的内容。

## 项目结构 (Project Structure)

```
The-Asymmetrical-Time/
├── book1-不对称时间/          # 第一部作品
│   ├── chapters/              # 章节内容
│   │   └── chapter-template.md
│   └── README.md
│
├── book2-续作/                # 第二部作品（续作）
│   ├── chapters/              # 章节内容
│   │   └── chapter-template.md
│   └── README.md
│
├── characters/                # 角色档案
│   ├── main/                  # 主要角色
│   ├── supporting/            # 次要角色
│   ├── minor/                 # 其他角色
│   ├── character-template.md # 角色模板
│   └── README.md
│
├── worldbuilding/             # 世界设定
│   ├── geography.md           # 地理设定
│   ├── history.md             # 历史背景
│   ├── society.md             # 社会结构
│   ├── systems.md             # 技术/魔法系统
│   ├── timeline.md            # 时间线
│   └── README.md
│
├── outlines/                  # 大纲
│   ├── book1-outline.md       # 第一部大纲
│   ├── book2-outline.md       # 第二部大纲
│   ├── series-overview.md     # 系列总览
│   └── README.md
│
└── README.md                  # 本文件
```

## 快速开始 (Getting Started)

### 1. 规划阶段 (Planning Phase)

开始创作前，建议先完成以下工作：

1. **填写系列总览** (`outlines/series-overview.md`)
   - 确定系列的整体方向和主题
   - 规划各部作品的关系

2. **完善第一部大纲** (`outlines/book1-outline.md`)
   - 如果第一部已完成，记录其内容
   - 如果还在创作中，完善大纲

3. **规划第二部大纲** (`outlines/book2-outline.md`)
   - 确定续作的方向
   - 规划与第一部的联系

### 2. 世界设定 (Worldbuilding)

在 `worldbuilding/` 目录中建立详细的世界设定：

- **地理设定** (`geography.md`)：记录重要地点
- **历史背景** (`history.md`)：建立世界历史
- **社会结构** (`society.md`)：定义社会规则
- **技术/魔法系统** (`systems.md`)：建立规则系统
- **时间线** (`timeline.md`)：整理事件顺序

### 3. 角色创建 (Character Creation)

使用 `characters/character-template.md` 为每个角色创建档案：

1. 复制模板到相应目录（`main/`、`supporting/` 或 `minor/`）
2. 重命名为角色名（如：`张三.md`）
3. 填写角色信息

### 4. 开始写作 (Start Writing)

#### 第一部（如果还在创作中）

在 `book1-不对称时间/chapters/` 中：

1. 复制 `chapter-template.md`
2. 重命名为 `chapter-01.md`（或其他有意义的名称）
3. 开始写作

#### 第二部（续作）

在 `book2-续作/chapters/` 中：

1. 确保已完成第二部大纲
2. 复制 `chapter-template.md`
3. 重命名并开始创作

## 使用建议 (Tips)

### 保持一致性 (Consistency)

- 经常参考 `worldbuilding/` 中的设定
- 检查 `characters/` 中的角色信息
- 对照 `worldbuilding/timeline.md` 确保时间线正确

### 记录想法 (Track Ideas)

- 随时在相应的 README 或备注部分记录想法
- 使用伏笔跟踪功能记录未来要展开的线索

### 版本控制 (Version Control)

- 定期提交更改到 Git
- 使用有意义的提交信息
- 可以为重要版本创建标签

### 灵活调整 (Stay Flexible)

- 模板和结构是建议，不是限制
- 根据实际创作需要调整
- 最重要的是保持创作的流畅性

## 工作流程建议 (Suggested Workflow)

### 对于续作创作

1. **回顾第一部**
   - 重读或整理第一部的主要内容
   - 在 `book1-不对称时间/` 中记录关键信息

2. **规划续作**
   - 完善 `outlines/book2-outline.md`
   - 确定要延续和解决的情节线

3. **准备设定**
   - 更新 `worldbuilding/` 中的相关设定
   - 添加第二部的新元素

4. **创建/更新角色**
   - 更新现有角色的发展计划
   - 创建新角色档案

5. **开始写作**
   - 按章节逐步创作
   - 保持与设定的一致性

6. **定期回顾**
   - 检查情节连贯性
   - 确保角色发展合理
   - 验证伏笔和线索

## 贡献指南 (Contributing)

如果有多人协作：

- 在修改共享文件前先沟通
- 使用分支进行大的改动
- 及时同步和合并更改

## 许可 (License)

[根据需要添加许可信息]

---

**开始你的创作之旅吧！** 🚀

如有任何问题或建议，欢迎随时调整这个结构以适应你的创作需求。