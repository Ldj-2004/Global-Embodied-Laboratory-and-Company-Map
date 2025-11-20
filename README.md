<div align="center">

# 🌍 Global Embodied Laboratory and Company Map
### 全球具身智能实验室与公司地图

[![Team](https://img.shields.io/badge/Team-PJLab__IPEC-blue?style=flat-square&logo=google-chrome)](https://www.pjlab-ipec.com/)
[![Updates](https://img.shields.io/badge/Updates-2024-green?style=flat-square)](https://github.com/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

**[ 🌐 访问我们的团队主页 ](https://www.pjlab-ipec.com/)**

</div>

---

## 📖 项目介绍 | Introduction

本项目致力于收集并展示全球范围内**具身智能 (Embodied AI)** 相关的顶尖实验室与创新公司。我们通过**可视化地图**与**详细数据表格**两种形式，为您呈现该领域的全球布局与核心力量。

## 🗺️ 地图功能 | Map Visualization

我们提供了交互式的地图体验，帮助您快速定位和获取信息：

### 1. 视图模式 (View Modes)
- 🌡️ **热力图模式 (Heatmap)**：直观展示全球具身智能资源的聚集程度。
- 📍 **普通模式 (Normal)**：精确查看每一个机构的地理位置。
- 🧭 **快速导航**：左上角提供地域切换功能，支持快速跳转至不同大洲或国家。

### 2. 详细信息交互 (Interaction)
点击地图上的 **公司** 🏢 或 **学校** 🎓 图标，将弹出详细信息页，包含以下内容：
- **基本信息**：名称、成立时间、简介。
- **核心团队**：主要人物 (PI / Founders)。
- **研究概况**：研究方向、代表性论文 (Works) 或产品 (Products)。
- **外部链接**：
    - 点击公司图标可直接跳转至官网。
    - 学校实验室主页已整合至信息页中，方便一站式浏览。

<!-- 如果你有地图的截图，建议在这里放一张图，看起来会更直观 -->
<!-- ![Map Demo](图片链接) -->

---

## 📊 数据列表 | Data Tables

以下是整理后的详细数据列表。

<!-- 请在下方粘贴你的表格 Markdown 代码 -->

### 🏫 全球实验室列表 (Laboratories)

<!-- 这里留给表格1 -->

### 🏢 创新公司列表 (Companies)

<!-- 这里留给表格2 -->

---

## 🤝 贡献 | Contribution
如果您发现有遗漏的实验室或公司，欢迎提交 PR 或通过 Issue 联系我们。

Copyright © PJLab IPEC. All Rights Reserved.
```

**修改亮点：**
*   **居中标题与徽章**：让页面头部看起来像一个成熟的开源项目。
*   **双语/清晰的小标题**：使用了 Emoji 和清晰的层级（##, ###），让阅读体验更好。
*   **结构化列表**：将原本的一大段文字拆分成了功能点列表。

---

### 第二步：如何添加 Excel (.xlsx) 表格到 README

GitHub 的 README 是基于 **Markdown** 语法的，它**不直接支持**嵌入 `.xlsx` 文件预览。你不能像在 Word 里那样直接插入附件。

你有以下三种主要方法将 Excel 数据放入 README：

#### 方法一：使用在线转换工具（推荐，最快）

如果你的表格数据不是特别大（例如几百行以内），直接转换成 Markdown 表格是展示效果最好的。

1.  打开你的 `.xlsx` 文件，**复制**你要展示的区域。
2.  打开这个网站：[TableConvert](https://tableconvert.com/excel-to-markdown) (或者搜索 "Excel to Markdown")。
3.  在左侧框中 **粘贴** 你的数据。
4.  右侧框会自动生成 Markdown 代码（看起来像很多 `|` 和 `-` 符号）。
5.  **复制** 右侧生成的代码。
6.  回到你的 `README.md`，将代码粘贴到我上面模板中标记 `<!-- 这里留给表格... -->` 的位置。

#### 方法二：直接发给我（如果数据不敏感）

如果表格不是特别巨大，你可以直接把 Excel 里的内容复制，粘贴到这里发给我，我帮你转换成 Markdown 格式的代码，你直接复制即可。

#### 方法三：上传文件并添加下载链接（如果表格巨大）

如果你的表格有几千行，直接放在 README 里会让页面加载很慢且不仅容易阅读。建议这样做：

1.  把 `.xlsx` 文件上传到该 GitHub 仓库的根目录或 `data` 文件夹下。
2.  在 README 中添加下载链接，而不是直接展示表格。

**代码示例：**
```markdown
由于数据量较大，请点击下方链接查看完整表格：

- 📥 [下载全球实验室列表 (.xlsx)](./这里写你的文件名1.xlsx)
- 📥 [下载创新公司列表 (.xlsx)](./这里写你的文件名2.xlsx)
```

**💡 我的建议：**
如果是为了展示（Showcase），建议用**方法一**，截取表格中最重要的前 10-20 行数据放在 README 里作为预览，然后在下方按照**方法三**提供完整 Excel 文件的下载链接。这样既美观又实用。
