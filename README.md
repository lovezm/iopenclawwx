# iopenclawwx

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

目前小程序正在审核中，通过后应该就可以使用了 这是比较简单的接入到微信的方式
## 小程序码

![iOpenClaw 小程序码](https://github.com/lovezm/chatlog/blob/main/gh_498442564d0d_430.jpg?raw=true)

![41dad1186f45c7536daf7dd42d2414c4](https://github.com/user-attachments/assets/9b347747-772f-4983-b35e-1125db5ef3f2)

![3020261f694a93403b3849d1e070ee2d](https://github.com/user-attachments/assets/79eb1cf1-e3e9-43c0-aa6c-8ace7847ef50)

![525e4aa6d000d8bbe3149e65635328a2](https://github.com/user-attachments/assets/50736aea-635f-4d7b-8127-2bc7a7cadd22)

