<div align="center">

# MiniDataStructureWeb

**交互式数据结构可视化学习站**

一个基于纯前端技术的数据结构与算法交互式可视化教学平台，涵盖 24 种经典数据结构与算法，通过动画演示与交互操作帮助理解抽象概念。

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![jQuery](https://img.shields.io/badge/jQuery-3.6.0-0769AD?style=flat&logo=jquery&logoColor=white)
![ECharts](https://img.shields.io/badge/ECharts-5.x-AA344D?style=flat)
![Bootstrap](https://img.shields.io/badge/Bootstrap-3.4.1-7952B3?style=flat&logo=bootstrap&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-blue)

</div>

---

## 项目简介

本项目是一个**纯本地前端**的数据结构可视化教学网站，无需后端服务，无需构建工具，打开浏览器即可使用。每个数据结构对应一个独立页面，提供：

- **交互动画**：通过 CSS 动画和 ECharts 图表实时展示数据结构的操作过程
- **手动操作**：插入、删除、查找、排序等操作均可由用户自由控制
- **执行日志**：每步操作附带时间戳记录，便于回顾学习过程
- **多种可视化**：线性结构使用 DOM 动画，树/图/排序使用 ECharts 图表

## 数据结构清单

### 线性结构（7 个）

| 序号 | 名称 | 核心功能 |
|:---:|------|---------|
| 1 | 顺序存储线性表 | 数组实现，插入/删除/查找，动态容量，元素移动动画 |
| 2 | 链式存储线性表 | 单链表，节点创建/链接动画，按位置插入/删除 |
| 3 | 栈 | LIFO 结构，Push/Pop 动画，键盘快捷键支持 |
| 4 | 队列 | FIFO 线性队列，入队/出队动画，队头/队尾指针可视化 |
| 4-1 | 循环队列 | 环形布局可视化，取模运算演示，满/空状态判断 |
| 5 | 串 | 字符串初始化/插入/删除/替换/遍历，逐字符可视化 |
| 6 | 数组与矩阵 | 多维数组可视化，特殊矩阵（对称/稀疏），矩阵转置 |
| 7 | 广义表 | 递归结构，取头/取尾，深度/长度计算，多层结构可视化 |

### 树结构（10 个）

| 序号 | 名称 | 核心功能 |
|:---:|------|---------|
| 8 | 树 | 通用树，增删改节点，ECharts 树形渲染 |
| 9 | 二叉树 | 增删节点，前/中/后序遍历，路径显示，按值查询 |
| 14 | AVL 树 | 自平衡二叉搜索树，旋转操作可视化 |
| 15 | 伸展树 | 自顶向下 Splay 操作 |
| 16 | B 树 / B+ 树 | 多路搜索树可视化 |
| 19 | 自底向下伸展树 | 替代 Splay 实现 |
| 20 | 红黑树 | 自平衡 BST，颜色属性与旋转操作 |
| 21 | Treap 树 | BST + 堆性质，随机优先级 |
| 22 | FHQ Treap | 无旋转 Treap，Split/Merge 操作 |
| 24 | 配对堆 | 可合并优先队列，Decrease-Key 操作 |

### 图与网络（2 个）

| 序号 | 名称 | 核心功能 |
|:---:|------|---------|
| 10 | 图 | 增删节点/边，有向/无向切换，DFS/BFS 遍历，邻接矩阵+邻接表，度数统计 |
| 18 | 欧拉回路 | 欧拉回路/路径查找可视化 |

### 查找与哈希（2 个）

| 序号 | 名称 | 核心功能 |
|:---:|------|---------|
| 11 | 查找算法 | 逐步二分查找可视化，元素高亮 |
| 12 | 哈希表 | 5 种哈希函数 + 4 种冲突处理（线性探测/二次探测/再哈希/溢出区） |

### 排序算法（1 个）

| 序号 | 名称 | 核心功能 |
|:---:|------|---------|
| 13 | 排序 | **7 种排序算法**：冒泡/快速/插入/希尔/选择/归并/基数排序，升序/降序，比较/交换计数，ECharts 柱状图动画 |

### 高级结构（2 个）

| 序号 | 名称 | 核心功能 |
|:---:|------|---------|
| 17 | 左式堆 | 基于合并的优先队列 |
| 23 | KD 树 / KNN | K 维树空间查询，K 近邻搜索，散点图可视化 |

## 快速开始

### 环境要求

- 现代浏览器（Chrome / Firefox / Edge / Safari）
- 无需安装任何依赖

### 运行方式

**下载**
```
下载压缩包MiniDataStructureWeb.zip到本地
然后使用任意解压缩工具得到文件夹：MiniDataStructureWeb进入即可。
```

**方式一：直接打开**

```
双击 index.html 即可在浏览器中打开
```

### 实例展示

**操作界面**
```
<img src="/Sample_images/image1.png" alt="图片1" width="300"><br/>
![图片1](Sample_images/image1.png?raw=true)
<img src="/Sample_images/image (2).png" alt="图片2" width="300">
<img src="/Sample_images/image (3).png" alt="图片3" width="300">
<img src="/Sample_images/image (4).png" alt="图片4" width="300">
<img src="/Sample_images/image (5).png" alt="图片5" width="300">

```

## 项目结构

```
MiniDataStructureWeb/
├── index.html                    # 首页（卡片式导航）
├── css/
│   └── maps.css                  # 侧边栏导航样式
├── js/
│   ├── jquery-3.6.0.js           # jQuery
│   ├── echarts.js                # Apache ECharts（完整版）
│   └── echarts.min.js            # Apache ECharts（压缩版）
├── data_structures/              # 24 个数据结构可视化页面
│   ├── 1XianXingBiaoShun.html    # 顺序存储线性表
│   ├── 2XianXingBiaoLian.html    # 链式存储线性表
│   ├── 3stack.html               # 栈
│   ├── ...                       # （共 24 个 HTML 文件）
│   └── 24PeiDuiDui.html          # 配对堆
└── plugins/                      # 第三方库
    ├── bootstrap-3.4.1/          # Bootstrap CSS/JS/Fonts
    ├── bootstrap-datepicker-1.9.0/  # 日期选择器
    └── font-awesome-4.7.0/       # Font Awesome 图标
```

## 技术架构

### 技术选型

| 层级 | 技术 | 说明 |
|------|------|------|
| 结构层 | HTML5 | 语义化标签，每页独立 |
| 样式层 | CSS3 + Bootstrap 3.4.1 | 响应式布局，渐变/动画/阴影 |
| 交互层 | jQuery 3.6.0 | DOM 操作，事件处理 |
| 可视化层 | Apache ECharts 5.x | 树形图/网络图/柱状图/散点图 |
| 图标层 | Font Awesome 4.7.0 | 200+ 图标 |

### 架构设计

```
┌─────────────────────────────────────────────┐
│              index.html（首页）               │
│         卡片式导航，一键跳转各模块              │
└──────────────────┬──────────────────────────┘
                   │
    ┌──────────────┼──────────────────┐
    ▼              ▼                  ▼
┌────────┐  ┌────────────┐  ┌────────────────┐
│ 线性结构 │  │  树/图结构   │  │  查找/排序/哈希  │
│ DOM动画  │  │ ECharts渲染 │  │  ECharts+DOM   │
└────────┘  └────────────┘  └────────────────┘
    │              │                  │
    └──────────────┼──────────────────┘
                   ▼
        ┌─────────────────────┐
        │  共享组件：侧边栏导航   │
        │  操作日志 · CSS动画    │
        └─────────────────────┘
```

### 两种可视化方案

**DOM 动画**（线性结构 1-7）：
- 使用 `<div>` + CSS 定位构建节点、指针、箭头
- CSS `@keyframes` 实现插入/删除/移动动画
- 适合展示线性结构的顺序关系

**ECharts 图表**（树/图/排序 8-24）：
- Tree Graph：树结构可视化
- Graph (Force)：图的力导向布局
- Bar Chart：排序算法柱状图动画
- Scatter Plot：KD 树空间分区

## 功能特性

### 交互设计

- **自由操作**：插入、删除、查找、修改等操作完全由用户控制
- **参数配置**：可调整数据结构容量、排序顺序（升序/降序）、哈希函数等
- **实时反馈**：操作结果即时显示在可视化区域
- **操作日志**：带时间戳的操作记录，方便回溯

### 可视化效果

- **CSS 动画**：平滑的插入/删除/移动过渡效果
- **高亮标记**：查找/比较过程中元素高亮显示
- **颜色编码**：排序比较/交换使用不同颜色区分
- **渐变按钮**：现代化 UI 设计，圆角/阴影/悬停效果

### 响应式设计

- 侧边栏固定导航，所有页面快速切换
- 移动端自适应布局（`@media max-width: 768px`）

## 使用示例

### 1. 学习栈操作

打开 `3stack.html`，点击"入栈"按钮添加元素，点击"出栈"移除栈顶元素，观察 LIFO 原则的动画演示。

### 2. 比较排序算法

打开 `13PaiXu.html`，选择不同的排序算法（冒泡/快速/归并等），点击"下一步"逐步执行，观察比较和交换过程，查看比较/交换计数。

### 3. 探索哈希表

打开 `12Hash.html`，选择哈希函数（除留余数法/折叠法等），选择冲突处理方式（线性探测/再哈希等），插入元素观察哈希表的变化过程。

### 4. 可视化二叉树

打开 `9ErTree.html`，添加节点构建二叉树，执行前序/中序/后序遍历，观察递归过程的路径高亮。

## 开发说明

### 本地开发

本项目为纯本地站点，无外联库，无需构建步骤：

```bash
# 克隆仓库
git clone https://github.com/your-username/MiniDataStructureWeb.git

# 进入项目目录
cd MiniDataStructureWeb

# 启动本地服务器
python -m http.server 8080
```

### 添加新数据结构

1. 在 `data_structures/` 目录下创建新的 HTML 文件
2. 复制现有页面的侧边栏导航结构
3. 引入共享 CSS 和必要的 JS 库（jQuery、Bootstrap、ECharts）
4. 实现可视化逻辑和交互控制
5. 在侧边栏导航中添加新链接

### 项目规范

- 每个数据结构一个独立 HTML 文件
- 内联 `<script>` 和 `<style>`（当前架构）
- 中文界面，按钮和日志使用中文
- CSS 动画使用 `@keyframes` 定义

## 致谢

- [jQuery](https://jquery.com/) - DOM 操作与事件处理
- [Apache ECharts](https://echarts.apache.org/) - 数据可视化图表
- [Bootstrap](https://getbootstrap.com/) - 响应式 UI 框架
- [Font Awesome](https://fontawesome.com/) - 图标库

## 许可证

本项目采用 [MIT License](LICENSE) 开源许可证。

---

<div align="center">

**如果这个项目对你的学习有帮助，欢迎 Star 支持！**
</div>

<div align="center">
这是我2025年西南某某大学的毕业论文设计的简化版本，原始代码中套用了django+mysql支撑，更加灵活且面向生产工作环境。<br/>
但在这里只保留了核心内容，且为均已构建为本地库，更欢迎对数据结构学习和感兴趣的老师同学朋友使用。<br/>
————如果有需要可以联系我E-mail：dfhuh@foxmail.com————
</div>
