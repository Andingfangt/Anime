# Anime.js 学习项目

一系列独立的 HTML 示例，用于学习 anime.js 动画库。

## 📚 示例

### 1. 基础动画 (`examples/basic-animation.html`)
演示核心 `anime()` 函数的使用：
- CSS 变换：`translateX`、`opacity`、`rotate`
- 单个元素动画
- 平滑缓动效果 (`easeInOutQuad`)

**学习要点**：如何使用 anime.js 通过 CSS 属性和变换创建简单动画。

### 2. 时间线 (`examples/timeline.html`)
演示 `anime.timeline()` 用于编排多个动画：
- 3 个元素的顺序动画
- 时间偏移实现重叠效果 (`-=200`)
- 为所有动画设置默认参数

**学习要点**：如何创建具有精确时间控制的动画序列。

### 3. 交错动画 (`examples/stagger.html`)
演示 `anime.stagger()` 用于动画多个元素：
- 5 个元素交错延迟（每个 100ms）
- 缩放和淡入效果
- 波浪式动画模式

**学习要点**：如何在多个元素上创建级联动画效果。

### 4. 可拖拽元素 (`examples/draggable.html`)
演示 `anime.createDraggable()` 用于交互式元素：
- 单个可拖拽元素
- 移动区域限制 (`container: [0, 0, 500, 500]`)
- 平滑释放动画

**学习要点**：如何让元素具有拖拽交互功能。

## 🚀 如何运行

直接在浏览器中打开任意 HTML 文件：

```bash
# 使用文件管理器
# 双击 examples/ 目录中的任意 .html 文件

# 使用命令行（Linux）
xdg-open examples/basic-animation.html

# 使用命令行（macOS）
open examples/basic-animation.html

# 使用命令行（Windows）
start examples/basic-animation.html
```

无需构建工具或服务器 - anime.js 已下载到本地 `lib/` 目录。

如需更新 anime.js 版本，可从以下 CDN 下载：
- bootcdn（国内）：https://cdn.bootcdn.net/ajax/libs/animejs/3.2.2/anime.min.js
- jsdelivr：https://cdn.jsdelivr.net/npm/animejs@3.2.2/lib/anime.min.js

## 🔗 资源

- **官方文档**：[https://animejs.com/documentation/](https://animejs.com/documentation/)
- **缓动编辑器**：[https://animejs.com/easing-editor](https://animejs.com/easing-editor)
- **CodePen 示例**：[https://codepen.io/collection/Poerqa](https://codepen.io/collection/Poerqa)
- **GitHub 仓库**：[https://github.com/juliangarnier/anime](https://github.com/juliangarnier/anime)

## 🎯 学习目标

本项目帮助你学习：
1. 基础 anime.js API 使用（`anime()`、`timeline()`、`stagger()`、`createDraggable()`）
2. CSS 变换和属性动画
3. 动画时间和序列控制
4. 可拖拽元素的交互式动画

## 📦 项目结构

```
Anime/
├── README.md
├── lib/
│   └── anime.min.js
├── examples/
│   ├── basic-animation.html
│   ├── timeline.html
│   ├── stagger.html
│   └── draggable.html
```

## 💡 提示

- 每个示例都是独立的 - 文件之间无依赖关系
- 所有示例使用 anime.js v3.2.2（本地文件）
- 内联注释解释关键 API 概念
- 尝试修改数值来实验！

---

**享受动画创作！** 🎨