# iopenclawwx

可通过 iopenclaw 的微信小程序实现 OpenClaw 与个人微信之间进行通讯会话。

众所周知的原因，中国大陆无法使用 Telegram、WhatsApp 等工具与 OpenClaw 会话，虽然可以使用飞书、钉钉，但配置起来也比较复杂。而国民第一大 app 微信，却只支持企业微信，不支持个人微信。

iopenclawwx 也是来解决这个用户痛点的！将 OpenClaw 与微信小程序连接，可以直接通过微信小程序与 OpenClaw 进行对话，让 OpenClaw 做你让他做的事情。并且可以随时随地获得 OpenClaw 的回复。
✅ 完全免费：无需订阅，无需付费

✅ 极速接入

官网 https://iopenclaw.app
```bash
openclaw plugins install iopenclawwx
cd ~/.openclaw/extensions/iopenclawwx
npm run config-init  # 输入你的 API Key
openclaw gateway restart
```
```bash
[root@VM34698DE11A383E0 ~]# openclaw plugins install iopenclawwx

🦞 OpenClaw 2026.2.19-2 (45d9b20) — I speak fluent bash, mild sarcasm, and aggressive tab-completion energy.

│
◇  Doctor warnings ─────────────────────────────────────────────────────────────────────────╮
│                                                                                           │
│  - State dir migration skipped: target already exists (/root/.openclaw). Remove or merge  │
│    manually.                                                                              │
│                                                                                           │
├───────────────────────────────────────────────────────────────────────────────────────────╯
Downloading iopenclawwx…
Extracting /tmp/openclaw-npm-pack-9id2hN/iopenclawwx-0.0.2.tgz…
Installing to /root/.openclaw/extensions/iopenclawwx…
11:58:51 [plugins] plugins.allow is empty; discovered non-bundled plugins may auto-load: iopenclawwx (/root/.openclaw/extensions/iopenclawwx/index.ts). Set plugins.allow to explicit trusted ids.
Config overwrite: /root/.openclaw/openclaw.json (sha256 aa7b303ba098207dc576eec9a8d9781f9ef60780191a884ca9d1d1c48e870ae7 -> 0a1e2f43d5fb2722fe71e65db947655b54c229a892dcad83eaf0dd22432b8b2e, backup=/root/.openclaw/openclaw.json.bak, changedPaths=2)
Installed plugin: iopenclawwx
Restart the gateway to load plugins.
[root@VM34698DE11A383E0 ~]cd ~/.openclaw/extensions/iopenclawwx
[root@VM34698DE11A383E0 iopenclawwx]# npm run config-init

> iopenclawwx@0.0.2 config-init
> node scripts/config-init.js


════════════════════════════════════════
  iOpenClaw WX 配置初始化
════════════════════════════════════════
API Key（bot_xxx:secret）: b******************
✅ 已写入配置: /root/.openclaw/openclaw.json

ℹ 下一步执行: openclaw gateway restart
[root@VM34698DE11A383E0 iopenclawwx]# openclaw gateway restart
```


## 小程序码
![iOpenClaw 小程序码](https://github.com/lovezm/chatlog/blob/main/gh_498442564d0d_430.jpg?raw=true)

请我喝蜜雪
![3a8685b9f6660df9706496d99d01166c](https://github.com/user-attachments/assets/3f7a8993-ac55-40a7-a4d0-0340e59c868b)



