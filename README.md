# 个人英语学习网站制作

这是一个基于 VitePress 的英语学习网站 V0.1 内容浏览版。

## 当前包含内容

- 小学英语首页
- 小学英语词汇首页
- 家庭与人物词汇模块
- 30 个单词 Markdown 页面

## 本地预览

```bash
npm install
npm run docs:dev
```

## 构建静态网站

```bash
npm run docs:build
```

构建输出目录：

```text
.vitepress/dist
```

## Netlify 部署参数

```text
Build command: npm run docs:build
Publish directory: .vitepress/dist
```

## Vercel 部署参数

```text
Build command: npm run docs:build
Output directory: .vitepress/dist
Install command: npm install
```
