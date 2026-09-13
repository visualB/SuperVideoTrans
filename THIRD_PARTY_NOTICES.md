# 第三方许可声明 / Third-Party Notices

本软件（SuperVideoTrans）包含或调用以下第三方组件。请遵守各组件本身的许可条款。

SuperVideoTrans bundles or invokes the following third-party components. Please respect the license terms of each component.

---

## FFmpeg

- **版本 / Version**: 8.1.1 (essentials build, www.gyan.dev)
- **许可 / License**: GNU General Public License（GPL，编译配置含 `--enable-gpl`，且内置 x264 / x265 / xvid 等 GPL 组件）
- **源码 / Source**: https://ffmpeg.org/download.html
- **说明 / Note**: FFmpeg 以独立进程方式被本软件调用；其源码可于 ffmpeg.org 获取。

FFmpeg is invoked as a separate process by this software. Its source code is available at ffmpeg.org.

---

## Whisper (whisper.cpp)

- **程序 / Program**: whisper-cli (whisper.cpp)
- **许可 / License**: **MIT**（whisper.cpp © Georgi Gerganov）
- **源码 / Source**: https://github.com/ggml-org/whisper.cpp

---

## Whisper 模型 / Whisper Models

- **许可 / License**: **MIT**（模型权重源自 OpenAI Whisper，依其许可再发布）
- **来源 / Source**: https://github.com/openai/whisper
- **说明 / Note**: 模型由本软件在运行时从 ModelScope / HuggingFace 自动下载，并存放于用户本机 `models` 目录。

---

## .NET 9 (WPF)

- **许可 / License**: **MIT**
- **来源 / Source**: https://dot.net / https://github.com/dotnet/wpf

---

## CommunityToolkit.Mvvm

- **版本 / Version**: 8.4.0
- **许可 / License**: **MIT**
- **来源 / Source**: https://github.com/CommunityToolkit/dotnet

---

## 在线服务 / Online Services（非捆绑组件）

以下为运行时调用、与本软件无依赖关系的公开接口，其名称、服务与所有权益归各权利方所有：

The following online interfaces are called at runtime only and are not bundled with this software. All names, logos, services and rights belong to their respective owners:

| 服务 / Service | 权利方 / Owner |
| --- | --- |
| Microsoft Edge Translate / Edge-TTS | Microsoft |
| Google Translate / Google Translate TTS | Google |
| Baidu Translate (百度翻译 API) | Baidu |
| DeepL | DeepL GmbH |
| OpenAI 兼容接口 / CosyVoice | 各权利方 |

本软件仅以公开接口方式调用，不包含未经授权的内容，亦不对接口可用性负责。

---

## 最终用户须知 / End User Notice

- 本软件**不捐赠代任何第三方服务商**，也不提供内置密钥。
- 使用本软件时，语音与文本数据将被发送至所选服务方，请自行评估隐私与合规风险。
- 如任一组件权利方对授权有异议，请联系作者移除相应组件。

**This software does NOT represent or affiliate with any third-party service provider, and does not bundle any service credentials. Audio/text data is sent to the service you choose — evaluate privacy and compliance accordingly.**