# webrtc-build

[![GitHub tag (latest SemVer)](https://img.shields.io/github/tag/shiguredo-webrtc-build/webrtc-build.svg)](https://github.com/shiguredo/momo)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Actions Status](https://github.com/rabe1028/webrtc-build/workflows/build/badge.svg)](https://github.com/rabe1028/webrtc-build/actions)

## About Support

We check PRs or Issues only when written in JAPANESE.
In other languages, we won't be able to deal with them. Thank you for your understanding.

## webrtc-build について

様々な環境向けの WebRTC のビルドを行って、そのバイナリを提供しています。

## ダウンロード

[リリース](https://github.com/melpon/webrtc-build/releases) からダウンロードしてください。

## パッケージに入っている内容

- WebRTC ライブラリ(webrtc.lib あるいは libwebrtc.a)
- WebRTC のインクルードヘッダ
- WebRTC のバージョン情報(コミットハッシュ)

## 現在提供しているビルド

- windows
- macos
- raspbian-buster_armv6 (Raspberry Pi Zero)
- raspbian-buster_armv7 (Raspberry Pi 3, 4)
- ubuntu-16.04_armv7
- ubuntu-16.04_x86_64
- ubuntu-18.04_armv8 (Jetson Nano)
- ubuntu-18.04_x86_64

## 開発について

webrtc-build はオープンソースソフトウェアですが、開発についてはオープンではありません。 そのためコメントやプルリクエストを頂いてもすぐには採用はしません。

## ライセンス

Apache License 2.0

```
Copyright 2019, Shiguredo Inc, melpon, enm10k, tnoho and kdxu

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
