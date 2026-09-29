# xiaogao860 · 个人空间

一个轻量的个人介绍网站，采用原生 HTML 和 CSS 编写，没有构建依赖。页面只保留「关于我」和「保持联系」两部分，使用深色 Liquid Glass 风格、红色强调和半透明玻璃卡片。

## 内容修改

- `index.html`：修改首页介绍、「关于我」列表、项目简介、学习方向和电话、邮箱联系方式。
- `styles.css`：调整颜色、布局、玻璃质感和移动端样式。
- `favicon.svg`：修改浏览器标签页图标。

目前页面介绍北邮计算机在读和 BUPT3DAO 成员身份，并展示 Web3 学习方向、BUPT3DAO 官网和 Anime Player Android 项目。页面中的电话和邮箱会作为公开联系方式显示。

## 本地预览

在仓库根目录运行：

```bash
python3 -m http.server 8000
```

然后访问 `http://localhost:8000`。

## GitHub Pages 部署

仓库已包含 `.github/workflows/pages.yml`。将改动推送到 `main` 后，GitHub Actions 会自动发布到：

`https://xiaogao860.github.io/XG-s-blog/`

首次发布前，在 GitHub 仓库设置中打开 **Settings → Pages**，将 **Build and deployment → Source** 设为 **GitHub Actions**。部署状态可以在仓库的 **Actions** 页面查看。
