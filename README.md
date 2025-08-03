# 学习笔记博客

这是一个基于GitHub Pages和Cayman主题搭建的学习笔记博客。用于记录学习过程中的知识点、心得体会和项目实践。

## 功能特点

- 简洁美观的Cayman主题
- 响应式设计，适配各种设备
- 支持Markdown语法编写笔记
- 自动生成笔记分类和归档
- 支持本地预览和GitHub Pages部署

## 目录结构

```
learning_blog/
├── _config.yml         # 网站配置文件
├── _includes/          # 包含文件
├── _layouts/           # 页面布局
├── _posts/             # 学习笔记文章
├── _sass/              # 样式文件
├── assets/             # 静态资源
├── index.md            # 博客主页
├── another-page.md     # 示例页面
├── LICENSE             # 许可证
├── README.md           # 项目说明
└── 个性化修改指南.md    # 自定义指南
```

## 本地预览

1. 安装Ruby和Jekyll
   ```bash
   # 安装Ruby
   # 访问 https://www.ruby-lang.org/zh_cn/downloads/ 下载并安装

   # 安装Jekyll
   gem install jekyll bundler
   ```

2. 安装依赖
   ```bash
   cd learning_blog
   bundle install
   ```

3. 运行本地服务器
   ```bash
   bundle exec jekyll serve
   ```

4. 在浏览器中访问 `http://localhost:4000` 预览网站。

## 部署到GitHub Pages

1. 创建GitHub仓库，命名为 `learning_blog`
2. 将代码推送到GitHub仓库
   ```bash
   git init
   git add .
   git commit -m "初始化学习笔记博客"
   git remote add origin https://github.com/你的GitHub用户名/learning_blog.git
   git push -u origin main
   ```
3. 在仓库设置中启用GitHub Pages
   - 选择 `main` 分支作为源
   - 选择根目录作为发布目录
4. 等待几分钟，访问 `https://你的GitHub用户名.github.io/learning_blog` 查看部署后的网站。

## 个性化修改

请参考 `个性化修改指南.md` 文件，了解如何自定义博客的样式、布局和内容。

## 许可证

本项目使用 [MIT](LICENSE) 许可证。
