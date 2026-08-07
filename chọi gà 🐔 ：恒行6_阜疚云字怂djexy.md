恒行6【Q-——333307——】恒行6【 辋芷《888yx●vip》 】
恒行6【Q-——333307——】恒行6【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程

还在羡慕别人的技术博客？其实，利用 GitHub Pages 配合 Hexo 框架，你可以在半小时内拥有一个完全属于自己的免费博客。本文手把手教你完成从环境搭建到域名绑定的全流程，建议收藏！

 为什么选择 GitHub Pages + Hexo？

- 完全免费：托管在 GitHub 服务器，无需购买云主机
- 极致速度：国内访问速度尚可，且支持 HTTPS
- 版本管理：所有文章都是 Markdown 文件，天然支持 Git 版本控制
- 主题丰富：Hexo 拥有上千款精美主题，总有一款适合你

 第一步：环境准备（5分钟搞定）

在开始之前，请确保你的电脑已经安装：
1. Node.js（建议 v14+）—— 前往官网下载安装包
2. Git —— 用于代码版本管理

 第二步：安装 Hexo 并初始化项目

打开终端，输入以下命令：

```bash
npm install -g hexo-cli
hexo init my-blog
cd my-blog
npm install
```

这条命令会创建一个包含基本结构的博客项目，`_config.yml` 文件是全局配置，可以修改站点标题、描述、关键词等 SEO 信息。

 第三步：写文章并本地预览

在 `source/_posts` 目录下创建 `.md` 文件，头部记得加上：

```
---
title: 我的第一篇文章
date: 2024-01-01
tags: [教程]
---
```

然后运行 `hexo s` 即可在 `http://localhost:4000` 本地预览。

 第四步：部署到 GitHub Pages

1. 在 GitHub 新建仓库，命名为 `用户名.github.io`
2. 安装部署插件：`npm install hexo-deployer-git --save`
3. 修改 `_config.yml` 中的 deploy 配置：

```yaml
deploy:
  type: git
  repo: 你的仓库地址
  branch: main
```

最后运行 `hexo g && hexo d` 即可完成部署，浏览器访问 `用户名.github.io` 就能看到博客了。

 进阶技巧：绑定自定义域名

在仓库设置 → Pages 中，填入你的域名，然后在 DNS 服务商添加 CNAME 记录指向 `用户名.github.io`，最后在 `source` 目录创建 CNAME 文件写入域名即可。

 总结与互动

通过以上步骤，你已经成功搭建了属于自己的技术博客。接下来你可以：
- 更换喜欢的主题，定制个性化页面
- 使用 `hexo new post "文章名"` 快速创建新文章
- 配置 RSS 订阅和站点地图提升 SEO

你准备用博客记录什么内容？ 是技术笔记还是生活随笔？欢迎在评论区分享你的想法，遇到任何问题也可以在下方留言，我会第一时间回复！

如果你觉得这篇教程有帮助，别忘了 点赞 + 转发，让更多小伙伴学会搭建自己的博客！关注我，后续还会带来更多 SEO 优化 和 博客美化 的实战技巧。

相关推荐：

https://github.com/garrisonanthony923/xbqyss/blob/main/C%E1%BB%91c%20Games%20%F0%9F%A5%8A%EF%BC%9A%E6%81%92%E8%A1%8C5%E5%AE%98%E6%96%B9%E6%B5%8B%E9%80%9F_%E4%BA%AE%E6%8A%80%E7%A6%84%E6%B1%BE%E8%B0%9Fexyyt.md

<img src="https://i.postimg.cc/k5ShNbSr/hengxing6-00007.png" />

相关推荐：

https://github.com/garrisonanthony923/xbqyss/commit/1f1c1be88f6f0de3d213a6e9d942c995101bc5ee

<img src="https://i.postimg.cc/vBd20Z7v/hengxing6-00009.png" />
相关推荐：

https://github.com/powerslisa3278/hyaiwx/blob/main/Tr%E1%BB%B1c%20tuy%E1%BA%BFn%20%F0%9F%90%93%EF%BC%9A%E6%81%92%E8%A1%8C5%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80_%E6%92%BC%E8%8A%82%E8%AE%AF%E5%B1%91%E6%9C%94ntooc.md

<img src="https://i.postimg.cc/x86sjGw5/hengxing6-00013.png" />
相关推荐：

https://github.com/powerslisa3278/hyaiwx/commit/caa4a71528dd98a3624fad73b27e2c2431f5657d

<img src="https://i.postimg.cc/k5ShNbSr/hengxing6-00007.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
