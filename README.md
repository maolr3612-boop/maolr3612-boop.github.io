# 毛龙锐 · 个人作品集

本仓库是个人简历与作品集的 GitHub Pages 静态发布目录。主页入口为根目录 `index.html`，包含原有黑金视觉、连续三维人物、响应式简历与三个作品。

## 发布

GitHub Settings → Pages → Deploy from a branch → main → /(root)。`.nojekyll` 保证静态资源原样提供，无需 Jekyll 或 Node.js 构建。

请保留 `assets/`、`projects/`、`data/` 与全部 CSS/JavaScript 文件。仅上传 index.html 会导致模型、封面与作品数据丢失。

## 后续维护

可维护完整工程保留在 WorkBuddy 本地项目 `maolongrui-portfolio-handoff`，源数据为 `src/data/works.json`，页面为 `public/index.html`，三维源码为 `src/model-viewer.js`。

在完整工程执行 `npm run export:workbuddy` 后，将 `dist/workbuddy/` 内的全部文件同步至本发布仓库根目录，经确认提交到 main，GitHub Pages 即会构建更新。

此发布版本的作品库为只读展示，通过源文件修改后重新发布即可更新。FitLead 与筑境沿用原独立演示链接；它们的云端账号、AI 与业务后台不由本仓库运行。

原 Cloudflare 网站及 Sites 入口保持不变。本仓库不包含任何 API Key、部署 Token、OAuth 缓存或后台数据库。
