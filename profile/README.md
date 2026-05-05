<div align="center">

# 🍊 OrangeCloud IM SDK

**跨平台即时通信 SDK — 为直播、社交、协作场景而生**

[![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)](https://github.com/OrangeCloud-SDK/orangecloud-im-flutter)
[![iOS](https://img.shields.io/badge/iOS-000000?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/OrangeCloud-SDK/orangecloud-im-ios)
[![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://github.com/OrangeCloud-SDK/orangecloud-im-android)
[![Web](https://img.shields.io/badge/Web-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://github.com/OrangeCloud-SDK/orangecloud-im-web)

</div>

---

## ✨ 特性

- 🚀 **高性能** — 基于 SignalR 长连接，毫秒级消息送达
- 📱 **全平台** — Flutter / iOS / Android / Web / 小程序，一套 API 全覆盖
- 🔄 **自动重连** — 内置指数退避重连策略，断网恢复无感知
- 👥 **群组管理** — 加入/退出房间、在线人数、成员列表
- 💬 **丰富消息** — 文本、礼物、弹幕、系统公告、关播通知
- 🔒 **安全鉴权** — HMAC-SHA256 签名 + 域名白名单 + 包名校验
- 📊 **用量统计** — DAU、消息量、峰值连接数实时监控

---

## 📦 SDK 仓库

| 平台 | 仓库 | 安装方式 |
|:---:|------|----------|
| 🐦 Flutter | [orangecloud-im-flutter](https://github.com/OrangeCloud-SDK/orangecloud-im-flutter) | `git` 依赖 in pubspec.yaml |
| 🍎 iOS | [orangecloud-im-ios](https://github.com/OrangeCloud-SDK/orangecloud-im-ios) | Swift Package Manager |
| 🤖 Android | [orangecloud-im-android](https://github.com/OrangeCloud-SDK/orangecloud-im-android) | AAR 本地引用 |
| 🌐 Web | [orangecloud-im-web](https://github.com/OrangeCloud-SDK/orangecloud-im-web) | npm / 直接引用 |
| 🎮 Demos | [orangecloud-im-demos](https://github.com/OrangeCloud-SDK/orangecloud-im-demos) | 四端完整示例 |

---

## 🚀 快速开始

### Flutter
```yaml
dependencies:
  orangecloud_im_client:
    git:
      url: https://github.com/OrangeCloud-SDK/orangecloud-im-flutter.git
      ref: v1.0.0
```

### iOS (Swift Package Manager)
```swift
.package(url: "https://github.com/OrangeCloud-SDK/orangecloud-im-ios.git", from: "1.0.0")
```

### Android
下载 [AAR](https://github.com/OrangeCloud-SDK/orangecloud-im-android/releases) 放入 `libs/` 目录：
```kotlin
implementation(files("libs/orangecloud-im-client-release.aar"))
```

### Web
```html
<script src="dist/index.js"></script>
```

---

## 💰 套餐

| | 免费版 | 基础版 ¥399/月 | 专业版 ¥999/月 |
|--|:---:|:---:|:---:|
| DAU | 100 | 10,000 | 100,000 |
| 房间数 | 3 | 50 | 无限 |
| 单房间人数 | 50 | 500 | 5,000 |
| 每日消息 | 1万 | 50万 | 不限 |
| 消息存储 | - | 7天 | 30天 |
| Webhook | ❌ | ❌ | ✅ |

---

## 📖 文档

完整的接入文档、API 参考和最佳实践，请访问我们的开发者文档站。

---

<div align="center">

**OrangeCloud** — 让实时通信触手可及

</div>
