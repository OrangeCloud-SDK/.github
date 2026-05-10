<div align="center">

# 🍊 OrangeCloud SDK

**企业级云服务 SDK — 为直播、社交、视频场景提供全栈解决方案**

[![GitHub Org](https://img.shields.io/badge/GitHub-OrangeCloud--SDK-181717?style=for-the-badge&logo=github)](https://github.com/OrangeCloud-SDK)

</div>

---

## 🎯 产品矩阵

### 💬 IM SDK — 即时通信

为直播间、社交、协作场景提供实时消息能力。基于 SignalR 长连接，支持群组消息、在线状态、礼物弹幕、禁言管理。

| 平台 | 仓库 | 安装方式 |
|:---:|------|----------|
| 🐦 Flutter | [orangecloud-im-flutter](https://github.com/OrangeCloud-SDK/orangecloud-im-flutter) | Git 依赖 / pub |
| 🍎 iOS | [orangecloud-im-ios](https://github.com/OrangeCloud-SDK/orangecloud-im-ios) | Swift Package Manager |
| 🤖 Android | [orangecloud-im-android](https://github.com/OrangeCloud-SDK/orangecloud-im-android) | AAR 引用 |
| 🌐 Web | [orangecloud-im-web](https://github.com/OrangeCloud-SDK/orangecloud-im-web) | npm / JS 引用 |
| 🎮 Demos | [orangecloud-im-demos](https://github.com/OrangeCloud-SDK/orangecloud-im-demos) | 四端完整示例 |

**核心特性：** 毫秒级送达 · 自动重连 · 群组管理 · 礼物/弹幕 · 敏感词过滤 · 域名白名单 · Webhook 回调

---

### 🎬 Player SDK — 视频播放器

企业级跨平台视频播放器，支持点播/直播、DRM 加密、字幕、画中画、短视频模式、离线下载。

| 平台 | 仓库 | 安装方式 |
|:---:|------|----------|
| 🐦 Flutter | [orangecloud-player-flutter](https://github.com/OrangeCloud-SDK/orangecloud-player-flutter) | Git 依赖 / pub |
| 🍎 iOS | [orangecloud-player-ios](https://github.com/OrangeCloud-SDK/orangecloud-player-ios) | Swift Package Manager |
| 🤖 Android | [orangecloud-player-android](https://github.com/OrangeCloud-SDK/orangecloud-player-android) | AAR 引用 |
| 🌐 Web | [orangecloud-player-web](https://github.com/OrangeCloud-SDK/orangecloud-player-web) | npm / JS 引用 |
| 🎮 Demos | [orangecloud-player-demos](https://github.com/OrangeCloud-SDK/orangecloud-player-demos) | 四端完整示例 |

**核心特性：** 点播/直播 · DRM 加密 · 多字幕 · 画中画 · 短视频模式 · 离线下载 · 智能预加载 · 自适应码率

---

## ✨ 为什么选择 OrangeCloud

| | OrangeCloud | 其他方案 |
|--|:---:|:---:|
| 全平台覆盖 | ✅ Flutter/iOS/Android/Web | 部分平台 |
| 开箱即用 | ✅ 5 分钟接入 | 复杂配置 |
| 按需付费 | ✅ 免费版起步 | 高门槛 |
| 源码可见 | ✅ 开源 SDK | 黑盒 |
| 中文支持 | ✅ 中文文档 + 技术支持 | 英文为主 |

---

## 💰 商业模式

SDK 开源免费，按 **API Key 订阅收费**：

- **免费版** — 体验全部功能，适合开发调试
- **基础版** — 满足中小型应用，¥399/月起
- **专业版** — 无限制 + 高级功能，¥999/月起

---

## 📖 快速开始

```dart
// Flutter - IM SDK
import 'package:orangecloud_im_client/orangecloud_im_client.dart';

final im = OrangeCloudIMClient();
await im.login(hubUrl, appId, userId, userSig);
await im.joinGroup('room_001');
im.onMessageReceived.listen((msg) => print(msg));
```

```dart
// Flutter - Player SDK
import 'package:orangecloud_player_client/orangecloud_player_client.dart';

final player = OrangeCloudPlayerClient();
await player.initialize(appId: 'your_app_id', licenseKey: 'your_key');
await player.play('https://example.com/video.m3u8');
```

---

<div align="center">

**OrangeCloud** — 让云服务触手可及

[IM 文档](#) · [Player 文档](#) · [联系我们](mailto:hi@rong.fan)

</div>
