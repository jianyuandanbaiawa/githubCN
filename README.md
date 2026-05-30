# GithubCN

> 由于个人精力不足，不再为此项目添加词条内容，如有余力，可 fork 本项目进行词条补充
> 目前项目由JIAOBAI-QWQ支持维护，保证持续更新
> 部分单词源于AI或者是机翻，出现疑问请提问

Github 浏览器中文汉化插件

## 安装 && 使用

支持的浏览器|使用方式
---|---
Edge|[Edge 应用商店](<https://microsoftedge.microsoft.com/addons/detail/githubcn/onlodfoebaobhmlhgcbddjngjbkdbfaj>)
Google Chrome|下载源代码拖放至扩展页

## 如何补充翻译词条？

所有的翻译内容都在在`src/js/content.js`中

```js
const allData = [
  [`English`, `英文`],
]
```
## 更新词条（2026/5/31）
### 1. 修复现有问题
在 content.js 中修复了以下问题：

- 第 7 行 ：修复了 [ s , \ `] 的空翻译 → [ s , 个 ]`
- 第 177 行 ：修复了 [ Create an account , \ `] 的空翻译 → [ Create an account , 创建账户 ]`
- 第 188 行 ：修复了拼写错误 [ Cancer , 取消 ] → [ Cancel , 取消 ]
- 第 358-365 行 ：删除了 8 个空的翻译条目 [\ `, ``]`
### 2. 新增翻译内容
从 GitHub 网站（主页、登录页、仓库页）收集并添加了 165+ 条新翻译 ，包括：

- 导航菜单 ：Platform（平台）、Solutions（解决方案）、Resources（资源）、Open Source（开源）等
- 功能按钮 ：Sign up（注册）、Sign up for GitHub（注册 GitHub）、Try GitHub Copilot（试用 GitHub Copilot）等
- 功能标签 ：Plan（计划）、Collaborate（协作）、Automate（自动化）、Secure（安全）等
- Copilot 相关 ：Explore GitHub Copilot（探索 GitHub Copilot）、Copilot Autofix 等
- Actions 相关 ：Explore GitHub Actions（探索 GitHub Actions）等
- 安全功能 ：GitHub Advanced Security、Dependabot、Secret Protection 等
- 页脚区域 ：Sitemap（网站地图）、What is Git?（什么是 Git？）、Manage cookies（管理 Cookie）等
- 社交媒体 ：GitHub on LinkedIn/X/YouTube/TikTok/Twitch 等
- 仓库页面 ：Security and quality（安全与质量）、Folders and files（文件夹和文件）、Latest commit（最新提交）等
