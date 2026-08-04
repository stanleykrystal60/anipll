蓝图官方主管【Q-——333307——】蓝图官方主管【 辋芷《888yx●vip》 】
蓝图官方主管【Q-——333307——】蓝图官方主管【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程

你是不是也想拥有一个完全属于自己的技术博客，却苦于服务器成本高、搭建流程复杂？别担心，今天这篇教程将手把手带你用 GitHub Pages + Hexo 免费搭建一个高颜值、支持自定义域名的静态博客。整个过程无需购买服务器，只需跟着操作，30分钟即可上线。

 为什么选择 GitHub Pages 与 Hexo？

在开始之前，我们先解决“为什么”的问题。GitHub Pages 是 GitHub 提供的免费静态网站托管服务，支持自定义域名和 HTTPS；而 Hexo 是一款基于 Node.js 的快速、简洁且高效的博客框架，支持 Markdown 语法，主题生态丰富。两者结合，既是程序员的标配，也是零成本建站的首选方案。

 第一步：环境准备与账号注册

1. 安装 Node.js：前往官网下载 LTS 版本，安装完成后在终端输入 `node -v` 验证。
2. 安装 Git：同样从官网下载，安装后配置全局用户名和邮箱。
3. 注册 GitHub 账号：如果你还没有，赶紧去注册一个。这是托管博客的基础。

 第二步：安装 Hexo 并初始化博客

打开终端，执行以下命令：

```bash
npm install -g hexo-cli
hexo init my-blog
cd my-blog
npm install
```

这一串命令会帮你搭建好 Hexo 的基本骨架。此时，你可以运行 `hexo server` 在本地预览效果，默认地址为 `http://localhost:4000`。

 第三步：部署到 GitHub Pages

首先，在 GitHub 上新建一个仓库，仓库名必须为 `你的用户名.github.io`。然后，修改 `_config.yml` 文件中的部署配置：

```yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io.git
  branch: main
```

安装部署插件后，依次执行：

```bash
npm install hexo-deployer-git --save
hexo clean && hexo generate
hexo deploy
```

等上几分钟，访问 `https://你的用户名.github.io`，你的博客就上线了！

 第四步：优化与自定义

想让博客更有个人特色？可以切换主题、绑定自己的域名，甚至接入评论系统（如 Gitalk）和百度统计。建议重点关注 SEO 设置，为每篇文章添加关键词和描述，方便搜索引擎收录。

 互动引导

搭建过程中你是否遇到过“卡壳”？比如部署后页面空白、域名解析失败等。欢迎在评论区留言，把你遇到的问题和解决方案分享出来，大家一起交流学习。如果你觉得这篇教程对你有帮助，别忘了点赞和转发给身边需要的朋友哦！

相关推荐：

https://github.com/klinegina28/bhjqeg/blob/main/2026%E7%A7%91%E6%8A%80%E6%8C%87%E5%8D%97%EF%BC%9A%E8%93%9D%E5%9B%BE%E6%B3%A8%E5%86%8C%E4%B8%BB%E7%AE%A1_%E5%AE%9E%E8%9C%97%E9%92%A1%E5%B9%B3%E8%90%84PPCWD.md

<img src="https://i.postimg.cc/c4bQRyjk/lantu-00008.png" />

相关推荐：

https://github.com/klinegina28/bhjqeg/commit/22ae7aa5ba0600265d467fdce03d0ecd1b82022c

<img src="https://i.postimg.cc/rmj4zvx9/lantu-00011.png" />
相关推荐：

https://github.com/brownbarbara40/yzuprm/blob/main/%E8%BF%9B%E9%98%B6%E5%AE%9E%E6%93%8D%E6%8C%87%E5%8D%97%EF%BC%9A%E8%93%9D%E5%9B%BE%E5%AE%98%E6%96%B9%E5%AE%98%E6%96%B9_%E8%8F%87%E6%B5%AA%E5%95%84%E4%B9%98%E8%B0%B4XQQQW.md

<img src="https://i.postimg.cc/kGjWYk5W/lantu-00006.png" />
相关推荐：

https://github.com/brownbarbara40/yzuprm/commit/eb9a2c5521a9cfabe4fb389f8456b92f0060d5ad

<img src="https://i.postimg.cc/mkZQwbTF/lantu-00005.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
