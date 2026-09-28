# GitHub Daily 项目精选

这是「小胡同学 · GitHub Daily」每日开源项目精选的静态网页仓库。

每天从 GitHub 社区发现 4 个值得体验的项目，覆盖以下方向：

1. 办公自动化：数据分析
2. 办公自动化：办公工作流
3. 办公自动化：办公工作台
4. 生活兴趣

每个项目页面会介绍项目用途、上手方式、AI 时代的成长空间和近期社区信号，并提供 GitHub 仓库链接。

## 在线阅读

- [打开项目精选首页](https://f-naonao.github.io/github-daily-project-picks/)
- [查看每日归档](https://f-naonao.github.io/github-daily-project-picks/archive/)

每天的页面按日期单独保存，链接示例：

```text
https://f-naonao.github.io/github-daily-project-picks/archive/YYYY-MM-DD.html
```

已发布的历史日期页面不会被之后的日报覆盖。

## 仓库内容

- `index.html`：当前首页
- `archive/`：按日期保存的历史页面
- `.nojekyll`：让 GitHub Pages 原样发布仓库文件

本仓库是公开仓库，只保存供阅读的静态 HTML 页面。飞书机器人配置、Webhook 和项目生成所用的本地配置不放在这里。

## 发布方式

日报由本机的 GitHub Daily 定时任务生成。任务会更新本仓库中的首页和日期归档，推送后由 GitHub Pages 发布；网页可访问后，再向飞书群发送日报消息和网页入口卡片。

网站托管在 GitHub Pages：<https://f-naonao.github.io/github-daily-project-picks/>。
