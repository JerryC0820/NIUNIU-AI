# NIUNIU AI

<div align="center">
  <img src="https://nai.ainivox.cn/assets/niuniu-ai.svg" width="112" alt="NIUNIU AI" />
</div>

<div align="center">
  面向 Photoshop 的多模型 AI 图像生成与局部编辑扩展
</div>

<div align="center">
  <a href="https://nai.ainivox.cn/">官网</a> ·
  <a href="https://github.com/JerryC0820/NIUNIU-AI/releases">安装器下载</a> ·
  <a href="release-notes/">版本说明</a>
</div>

## 核心功能

- 文生图、图生图、多参考图生成与批量结果管理。
- 一键读取 Photoshop 全图、当前图层和当前选区。
- 局部修复、去除文字、扩展填充、选区蒙版、羽化与原位回插。
- 火山引擎、OpenAI 兼容协议、Nano Banana / Gemini 等多接口管理。
- 图像模型与文本模型独立选择、在线拉取、连通性测试和额度查询。
- 提示词润色、参考图提示词反推和生成参数保存。
- 生成队列、任务取消、缩略图预览、历史记录与本地缓存。
- 邮箱与微信账户、轻量记录同步、会员状态和到期倒计时。

## 支持环境

- Windows 10 / 11
- Adobe Photoshop 2020–2026
- Adobe CEP 扩展运行环境

## 下载与更新

正式安装器可从[官网](https://nai.ainivox.cn/)或[公开发行仓库 Releases](https://github.com/JerryC0820/NIUNIU-AI/releases)下载。

插件检查更新时始终优先读取和下载腾讯云正式源；腾讯云不可用时才切换 Cloudflare 公共备源。安装前必须通过 SHA-256 校验，更新只覆盖运行文件，不删除历史生成缓存、接口配置、账户状态或 Photoshop 文档。

公开发行仓库只提供 `NIUNIU-AI-Setup-x.x.x.exe`、对应校验文件、README 和版本说明，不提供项目源码或源码压缩包。

## 接口与数据

- 支持自定义 Base URL、API Key、图像模型和文本模型。
- 推荐的 OpenAI 兼容中转服务：[BBAPI](https://bbapi.ainivox.cn/)。
- 未登录时接口配置保存在本机；登录后可加密同步到同一账户。
- 云端仅同步生成记录、参数和轻量缩略图，原始大图仍只保存在本地。
- API Key 不提交到仓库，管理端不显示明文密钥。

## 仓库分工

- `JerryC0820/NIUNIU-AI`：公开发行仓库，只存放安装器、校验文件、README、稳定版清单和版本说明。
- `JerryC0820/NIUNIU-AI-Source`：私人源码仓库，保存完整源码、构建脚本、测试和发布历史。
- 两个仓库的 `README.md` 保持完全一致；每次正式版本发布时同步对应版本说明。

## 客服

- QQ：`3132733035`

## 安全说明

- 不要向任何仓库提交真实 API Key、管理员密码、`.env`、SQLite 数据库或一次性引导文件。
- 使用第三方模型和中转服务时，请遵守对应平台条款并自行确认计费规则。

## 许可证

[MIT](LICENSE)
