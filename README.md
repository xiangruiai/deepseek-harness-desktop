# DeepSeek Harness Desktop

> [!NOTE]
> 本仓库已归档。安装包已迁移至 [xiangrui-toolkit · Releases](https://github.com/xiangruiai/xiangrui-toolkit/releases/tag/v1.2.0)，后续随工具箱统一发布。


非官方 macOS 桌面应用。打开就能用，Node.js 和 DeepSeek Harness 已经打在安装包里。图标使用 DeepSeek 鲸鱼。

本仓库**只提供安装包**，不公开桌面壳源码。由万涂幻象发布，不是 DeepSeek 官方客户端。

## 下载

- 安装包：[DeepSeek-Harness-Desktop-1.2.0-macOS-Apple-Silicon.dmg](https://github.com/xiangruiai/deepseek-harness-desktop/releases/download/v1.2.0/DeepSeek-Harness-Desktop-1.2.0-macOS-Apple-Silicon.dmg)
- 发布页：[Releases](https://github.com/xiangruiai/deepseek-harness-desktop/releases)

社区工具箱同步放了下载入口：[`xiangruiai/vantasma-toolkit`](https://github.com/xiangruiai/vantasma-toolkit) 的 `apps/deepseek-harness-desktop/`。

## 安装

1. 打开 DMG，把 `DeepSeek Harness.app` 拖进应用程序。
2. 若系统提示无法打开：Finder 里右键应用选打开；或执行 `xattr -cr "/Applications/DeepSeek Harness.app"`。
3. 打开应用即可。第一次在界面里填 API Key。

不需要单独安装 Node.js，也不需要先跑命令行。

目前只提供 Apple Silicon。日志在 `~/Library/Logs/DeepSeekHarness/`。

## 1.2.0

- 输入框支持粘贴文字和图片
- 启动不再误开 Finder 资源目录
- 可以拖动窗口

## 说明

DeepSeek 名称与鲸鱼标识归 DeepSeek AI。Harness 本体见 [deepseek-ai/deepseek-harness](https://github.com/deepseek-ai/deepseek-harness)。

## 许可

安装包按 MIT 分发，见 [LICENSE](LICENSE)。
