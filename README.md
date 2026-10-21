# Autumn Blog

基于 Hexo 和 Butterfly 的个人博客源码。文章使用 Markdown 编写，网站由 Hexo 生成静态页面。

## 环境要求

- Node.js 20.19.0 或更高版本
- npm

## 本地预览

```bash
npm install
npx hexo server
```

打开终端显示的本地地址预览博客。

## 写文章

新建文章：

```bash
npx hexo new post "文章标题"
```

文章会放在 `source/_posts/`，用 Markdown 编辑后保存即可。

新建草稿（默认不会出现在生成的网站中）：

```bash
npx hexo new draft "文章标题"
```

完成后发布草稿：

```bash
npx hexo publish "文章标题"
```

## 生成静态页面

```bash
npx hexo clean
npx hexo generate
```

生成结果位于 `public/`。GitHub Pages 尚未配置；启用 Pages 部署后，站点地址可使用 `https://autumn112358.github.io/autumn-blog/`。
