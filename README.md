# 豚餐

豚餐是一个 Windows 桌面外卖提醒应用，也是一个充满趣味的自律小工具，适合总是忙到忘记点外卖的打工人、or正在减肥的人。
用户可以设置多个每日提醒时间，比如午餐、下午茶、晚餐；到点后应用会弹出水豚主题视频提醒，点击“已点”即可关闭弹窗。

## 功能

- 支持新增、编辑、暂停和删除多个餐点提醒
- 提醒每天重复，错过时间不会补弹
- 弹窗播放本地视频，保持原比例，不放大、不全屏
- 主窗口关闭后托盘常驻
- 支持开机自启开关，默认关闭
- 本地保存提醒设置，不需要登录或联网

## 下载

前往 [Releases](https://github.com/potatoniniViber/tuncan-reminder/releases/latest) 下载最新版：

- `tuncan-reminder.exe`：无需安装，下载后直接运行。
- `SHA256SUMS.txt`：用于校验下载文件完整性。

下载后可直接运行便携版 exe。首次运行时，如果 Windows 安全提示未知发布者，请确认文件来源为本仓库 Release 后再继续。


## 本地开发

```powershell
npm install
npm test
npm start
```

构建 Windows 安装包和便携版：

```powershell
npm run dist
```

## 技术栈

- Electron
- 原生 HTML / CSS / JavaScript
- Node.js `node:test`
- electron-builder

## License

MIT
