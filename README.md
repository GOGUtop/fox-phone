# 狐映 · 平行世界 · 狐刻（完整载荷）

已将预设依赖的远程 Tavern Helper 注入脚本和其 bundled UI 资源一并保存：

- `tavern-helper-original.js`：完整远程 `inject.js`（约 229 KB）
- `bundled.html`：完整远程界面资源（约 968 KB）
- `fox映.json`：预设中的狐映提示词与隐藏正则
- `index.js` / `manifest.json`：SillyTavern 扩展入口

## GitHub 订阅安装

将整个目录上传到 GitHub，确保 `manifest.json` 位于仓库根目录；在酒馆扩展安装界面填写仓库 URL 订阅安装。

该版本把狐映、平行世界、狐刻所需的共享载荷放在同一个插件中。若酒馆版本要求 raw 地址，请使用仓库中 `manifest.json` 的 raw URL。
