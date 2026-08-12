# iNotes-Plus

> Notes 主题升级版

本主题为 iNotes 的升级版，基于以下上游：

- [getgridea/gridea-theme-notes](https://github.com/getgridea/gridea-theme-notes) — 最初的 Notes 主题
- [Gridea-Pro/gridea-pro-themes · themes/inotes](https://github.com/Gridea-Pro/gridea-pro-themes/tree/main/themes/inotes) — Gridea Pro 官方移植的 inotes（1.0.0）

![preview](./assets/media/preview.png)

## 信息

| 字段 | 值 |
|---|---|
| 目录名 | `inotes-Plus` |
| 版本 | `1.1.0` |
| 模板引擎 | `go` |

## 特性

相对原版 1.0.0 的增量：

- **亮/暗双主题**：页面右上角切换按钮，默认跟随系统，手动选择后通过 localStorage 记住
- **闪念页**（`/memos`）：热力图 + 闪念列表 + 分页
- **分类页**：单分类页 `category.html` + 分类列表 `categories.html`，与标签体系对称
- 文章列表与文章页新增分类展示；Disqus 评论主题跟随暗色模式


## 自定义参数

在应用「主题 → 自定义」里可以配置以下选项：

### SEO

| 参数 | 说明 | 默认值 |
|---|---|---|
| Meta Description | - | `` |

### 布局

| 参数 | 说明 | 默认值 |
|---|---|---|
| 内容区最大宽度 | 可填像素类型（如：320px）或百分比类型（如：38.2%） | `800px` |
| 正文内容文字大小 | px 或 rem（如 16px 或 1rem） | `16px` |
| 标题对齐 | 包含标题及日期、标签等信息部分 | `center` |
| 网站字体 | 默认系统字体栈或 Georgia | `-apple-system,...` |
| 是否显示文章目录 | 仅在宽屏时生效 | `true` |

### 颜色

| 参数 | 说明 | 默认值 |
|---|---|---|
| 内容区背景色 | 颜色字符串（如：`#EEEEEE`、`rgba(255, 255, 255, 0.9)`） | `#ffffff` |
| 网页背景色 | 颜色字符串（如：`#EEEEEE`、`rgba(255, 255, 255, 0.9)`） | `#ffffff` |
| 文字颜色 | 颜色字符串（如：`#EEEEEE`、`rgba(255, 255, 255, 0.9)`） | `rgba(0, 0, 0, 0.86)` |
| 链接颜色 | 颜色字符串（如：`#EEEEEE`、`rgba(255, 255, 255, 0.9)`） | `rgba(0,0,0,.98)` |
| 链接 Hover 颜色 | 颜色字符串（如：`#EEEEEE`、`rgba(255, 255, 255, 0.9)`） | `#006CFF` |
| 黑暗模式 | 显示页面右上角的明亮/黑暗切换按钮 | `true` |

### 社交

| 参数 | 说明 | 默认值 |
|---|---|---|
| Github | 链接地址 | `` |
| Twitter | 链接地址 | `` |
| 微博 | 链接地址 | `` |
| 知乎 | 链接地址 | `` |
| Facebook | 链接地址 | `` |

### 自定义样式

| 参数 | 说明 | 默认值 |
|---|---|---|
| 自定义CSS | 额外注入的 CSS | `` |

### 谷歌统计

| 参数 | 说明 | 默认值 |
|---|---|---|
| 跟踪 ID | UA-xxxxxxxxx-x | `` |

## 使用

1. 在 Gridea Pro 应用内「主题」页选择本主题
2. 在「自定义」里按需调整参数
3. 预览、发布

## 授权

本主题未单独声明 `LICENSE` 文件，按仓库约定视为 **MIT**。
