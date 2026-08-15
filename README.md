# DeepSeek Harness Desktop

非官方 macOS 桌面壳，把 [DeepSeek Harness](https://github.com/deepseek-ai/deepseek-harness) 的 Web UI 包成原生窗口。图标使用 DeepSeek 鲸鱼。

本仓库**只提供安装包**，不公开桌面壳源码。由万涂幻象发布，不是 DeepSeek 官方客户端。

## 下载

- 安装包：[DeepSeek-Harness-Desktop-1.0.0-macOS-Apple-Silicon.dmg](https://github.com/xiangruiai/deepseek-harness-desktop/releases/download/v1.0.0/DeepSeek-Harness-Desktop-1.0.0-macOS-Apple-Silicon.dmg)
- 发布页：[Releases](https://github.com/xiangruiai/deepseek-harness-desktop/releases)

社区工具箱同步放了一份：[`xiangruiai/vantasma-toolkit`](https://github.com/xiangruiai/vantasma-toolkit) 的 `apps/deepseek-harness-desktop/`。

## 安装

1. 先装 [Node.js 22+](https://nodejs.org)（目前只打了 Apple Silicon）。
2. 打开 DMG，把 `DeepSeek Harness.app` 拖进应用程序。
3. 若系统提示无法打开：Finder 里右键应用选打开；或执行 `xattr -cr "/Applications/DeepSeek Harness.app"`。
4. 首次启动会通过 `npx @deepseek-ai/dsh web` 拉起本地服务（`http://127.0.0.1:3080/`）。
5. 在界面里配置 API Key，或自行写入本机环境 / `~/.dsh`。

## 说明

- 关闭窗口会退出 App，已经在跑的 Harness 服务默认继续。
- 日志：`~/Library/Logs/DeepSeekHarness/`
- DeepSeek 名称与鲸鱼标识归 DeepSeek AI。

## 许可

安装包按 MIT 分发，见 [LICENSE](LICENSE)。
