# dsh-phrolova-splash-v1.0.0

弗洛洛专属开场动画：绯红扫描、视频、打字机字幕、左侧 Logo，支持 Enter 跳过。

> DeepSeek Harness（dsh）第三方插件。本仓库提供可直接安装的发布包。

## 下载

- [`dsh-phrolova-splash-v1.0.0.zip`](./dsh-phrolova-splash-v1.0.0.zip) —— 完整发布包（28.4 MB）

## 安装

1. 解压 `dsh-phrolova-splash-v1.0.0.zip`，得到目录 `dsh-flollo-splash`
2. 把 `dsh-flollo-splash` 整个目录放到：

   ```
   %USERPROFILE%\.dsh\external\
   ```

3. 在 `%USERPROFILE%\.dsh\profiles\desktop\package.json` 的 `dsh.profile.bundles` 中加入
   `@dsh-external/dsh-flollo-splash`，或使用 dsh 的插件管理面板安装
4. 重启 DeepSeek Harness

## 兼容性

| 项目 | 值 |
| --- | --- |
| 插件版本 | 1.0.0 |
| 声明的宿主版本范围 | `0.1.0-rc.6 - 0.2.2-rc.1` |
| 宿主平台 | web |
| 许可 | CC-BY-NC-SA-4.0 |

超出声明范围运行不保证稳定。

## 包内文件

| 文件 | 大小 |
| --- | --- |
| `cordis.patch.yml` | 0.1 KB |
| `package.json` | 0.8 KB |
| `README.md` | 0.9 KB |
| `assets/background.jpg` | 231.6 KB |
| `assets/GreatVibes-Regular.ttf` | 354.2 KB |
| `assets/splash.mp4` | 28417.9 KB |
| `assets/audio/初始.mp3` | 361.3 KB |
| `lib/client.js` | 20.5 KB |
| `lib/index.js` | 2.5 KB |

## 说明

本仓库仅托管发布包与说明文档，问题请在 Issues 中反馈。
