# Claude Archive · 个人资料库

这是一个本地优先的静态网页工具。上传到 GitHub Pages 后，可在同一个网站中管理聊天记录、Memory、Projects、Profile、Artifacts 和 Skills。

## 部署
1. 解压 ZIP。
2. 将 `index.html`、`chat-reader.html`、`README.md` 一起上传到新仓库根目录。
3. 在 GitHub 仓库 Settings → Pages 中选择 Deploy from a branch，分支选 `main`，目录选 `/(root)`。

## 聊天记录功能
- 导入 Claude 导出的 conversations JSON。
- 自动保存在当前浏览器，重新打开后恢复。
- 修改对话标题和消息文本。
- 单条删除、批量选择/删除消息。
- 批量选择/删除对话。
- 标记未整理、整理中、已完成。
- 将单条消息保存到 Memory。
- 导出聊天备份；资料库的完整备份会包含已保存的聊天数据。

## 重要说明
所有数据保存在当前浏览器的本地存储中，不会自动同步到其他设备。清理浏览器数据或更换设备前，请导出备份。大体积聊天记录可能超过浏览器本地存储限额，建议定期导出备份。删除前会要求确认，但删除后无法从页面撤销。
