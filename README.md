# PCL2 玩家公开信网站

## 计划发布时间
2026 年 10 月 24 日中午 12:00（北京时间，UTC+8）。

## 文件
- `index.html`：完整的响应式公开信网页。联署按钮指向腾讯文档表单。

## 发布方式（GitHub Pages）
1. 将 `index.html` 上传到仓库根目录（root），并提交到默认分支 `main`。
2. **在计划发布时**打开仓库 `Settings` → `Pages`。
3. 在 `Build and deployment` 中选择 `Deploy from a branch`；分支选择 `main`，目录选择 `/(root)`，保存。
4. 等 GitHub Pages 部署完成后，检查 Pages 设置页显示的网站地址并打开测试。

请注意：仓库中的源码是公开可见的；GitHub Pages 的正式网站需单独启用。GitHub Pages 本身不会因为网页中写了发布时间就自动定时上线。若要严格在中午 12 点正式发布，请在该时刻手动启用 Pages 或将正式网页文件合并到被 Pages 发布的分支。
