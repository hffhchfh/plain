# 我的第一个仓库 · 纯静态版

一个用来学习 Git 与 GitHub 的练习网站。整个项目只有一个 `index.html`，不需要 Node.js、不需要打包工具，打开就能看，改完就能提交。

## 这个页面是什么

页面用最简单的 HTML + CSS + 原生 JavaScript 写成，包含三个板块：

- 自我介绍：姓名、班级、学号等信息，供练习修改文本后提交改动
- 课程清单：用表格记录每周学习主题和完成状态
- 动手试试：一个点赞按钮，每点一次数字加一，用来体验「改动 → 提交 → 推送」的完整流程

页面底部还写了开启 GitHub Pages 的操作路径，方便把网页发布到公网。

## 技术栈

- HTML5 + CSS3（手写样式，无框架）
- 原生 JavaScript（无需构建）
- Git + GitHub（版本管理与托管）

## 项目结构

```
plain-static/
├── index.html   # 全部页面代码：结构、样式、脚本
└── README.md    # 本说明文件
```

## 本地预览

直接双击 `index.html`，或用浏览器打开该文件即可，不需要启动任何服务。

## 发布到 GitHub Pages

1. 打开仓库的 Settings → Pages
2. Source 选择 `Deploy from a branch`
3. Branch 选 `main`，目录选 `/(root)`，点击 Save
4. 稍等片刻，访问 `https://hffhchfh.github.io/plain/`

## 学习目标

- 理解工作区、暂存区、提交三者的关系
- 熟悉 `git add` / `git commit` / `git push` 的基本用法
- 通过改动页面内容并推送，观察 GitHub 上的提交记录变化
