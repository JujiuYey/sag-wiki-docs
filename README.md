# SAG Wiki Docs

SAG Wiki 的项目介绍与使用文档站，使用 [Rspress](https://rspress.dev/) 构建，并通过 GitHub Pages 发布。

主项目：[JujiuYey/sag-wiki](https://github.com/JujiuYey/sag-wiki)

## 本地开发

环境要求：Node.js 20.19+ 或 22.12+、pnpm 10+。

```bash
pnpm install
pnpm dev
```

构建并预览生产版本：

```bash
pnpm build
pnpm preview
```

## 目录结构

```text
sag-wiki-docs/
├── docs/                 # 文档内容与首页
├── theme/                # 自定义主题
├── rspress.config.ts     # Rspress 配置
└── .github/workflows/    # GitHub Pages 部署
```

## GitHub Pages

推送到 `main` 会触发 `.github/workflows/deploy-pages.yml`。在仓库的 `Settings > Pages > Build and deployment` 中将 Source 设置为 **GitHub Actions**。

站点地址：<https://jujiuyey.github.io/sag-wiki-docs/>
