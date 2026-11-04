# Orange Notebook · 橘白手记

Windows 屏幕最上面的一座小岛，陪你用 Claude Code。
A small island at the top of your Windows screen that keeps you company while you use Claude Code.

- 她在做什么、做完了没有，一眼就能看见
- Claude Code 要许可、要问你问题时，在岛上就能答
- 点开任何一个正在开的会话，看你说的、她说的、她干的活，还能直接接着说
- 另有手记、专注、剪贴板历史、今日 Token、音乐控制和通知

官网：https://note.fightingfirefox.site
MV《交给我》：https://www.bilibili.com/video/BV1XJnZ6TEku

## 下载

到 [Releases](https://github.com/fightingFirefox/orange-notebook/releases) 下载最新的 `OrangeNotebook-<版本>-portable.exe`，免安装，双击就能运行。

- 需要 Windows 11 64 位（Windows 10 没有测过）
- 会话、许可这些功能需要本机装了 Claude Code
- 这个包用的是个人签名，Windows 第一次会弹「Windows 已保护你的电脑」，点「更多信息 → 仍要运行」。不放心可以先核对 SHA256（每个版本的说明里都有）：

```powershell
Get-FileHash .\OrangeNotebook-1.2.1.0-portable.exe
```

## 隐私

- 不收集、不上传任何数据，全程在本机运行
- 读 Claude Code 的记录只在内存里用；默认不往 Claude Code 里写任何东西，「许可接管」是单独的开关，默认关
- 本机接口只听 127.0.0.1

## 问题与建议

在 [Issues](https://github.com/fightingFirefox/orange-notebook/issues) 里提就好。

## 署名与许可

- 角色原案 / 原画：ZipZipPipe，非商用二创授权
- 非官方同人作品，与 Anthropic 无关，没有使用 Anthropic 的标志或官方形象
- 请勿售卖或用于付费分发；转发时请保留这段说明并署名 ZipZipPipe
