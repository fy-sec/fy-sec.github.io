# fy-sec's Security Lab

一个用于记录个人网络安全学习过程的博客，主要包含三个方向：

- 学习笔记
- 靶场渗透测试
- SRC 漏洞挖掘与复盘

线上地址：<https://fy-sec.github.io>

## 内容原则

本站只发布合法授权的学习与测试内容，不公开未授权目标、客户数据、个人隐私、完整凭证或未过披露期的漏洞。

## 技术栈

- Astro
- Fuwari
- pnpm
- GitHub Actions
- GitHub Pages

## 目录结构

```text
src/content/posts/learning/   学习笔记
src/content/posts/labs/       靶场渗透
src/content/posts/src/        SRC 漏洞
src/content/spec/about.md     关于页
src/config.ts                 站点、导航和个人资料配置
```

## 本地开发

```bash
pnpm install
pnpm dev
```

## 构建与部署

```bash
pnpm build
```

推送到 `main` 分支后，GitHub Actions 会自动构建并发布到 GitHub Pages。

## 授权与披露

所有靶场和 SRC 内容均应在获得授权后进行，并在公开发布前完成脱敏和披露确认。
