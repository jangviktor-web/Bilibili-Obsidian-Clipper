# 隐私政策 / Privacy Policy

**Bilibili Obsidian Clipper** 尊重并保护用户隐私。本扩展不收集、不存储、不上传任何个人数据到任何第三方服务器。

## 数据处理方式

- **B 站字幕抓取**：所有网络请求均由你的浏览器直接向 Bilibili（www.bilibili.com、api.bilibili.com、aisubtitle.hdslb.com）发起，复用你本人的浏览器登录态，扩展开发者无法访问这些数据。
- **本地存储**：你的设置（如导出格式、Obsidian 地址与 Token）仅保存在浏览器本地（`chrome.storage.local`），不会同步到云端。
- **Obsidian 写入**：仅在你主动操作时，向你自己配置的本地 Obsidian Local REST API（127.0.0.1 / localhost）发送字幕内容。

## 权限用途

| 权限 | 用途 |
|---|---|
| `storage` | 保存扩展设置 |
| `scripting` / `sidePanel` | 在 B 站页面注入字幕抓取界面 |
| bilibili 相关域名 | 请求视频信息与字幕数据 |
| localhost / 127.0.0.1 | 连接本地 Obsidian Local REST API |

## 联系方式

如有隐私相关问题，请通过 GitHub Issues 联系：https://github.com/haixiong1997/Bilibili-Obsidian-Clipper/issues

*最后更新：2026-11-01*
