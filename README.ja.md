
[![CI Linux](https://github.com/pjsip/pjproject/actions/workflows/ci-linux.yml/badge.svg?branch=master)](https://github.com/pjsip/pjproject/actions/workflows/ci-linux.yml)
[![CI Mac](https://github.com/pjsip/pjproject/actions/workflows/ci-mac.yml/badge.svg?branch=master)](https://github.com/pjsip/pjproject/actions/workflows/ci-mac.yml)
[![CI Windows](https://github.com/pjsip/pjproject/actions/workflows/ci-win.yml/badge.svg?branch=master)](https://github.com/pjsip/pjproject/actions/workflows/ci-win.yml)
[![Bitrise iOS](https://img.shields.io/bitrise/70e79dc5-cae8-4cb7-a6cd-9a5bd3f3270f?token=tnXk2DZ71Zmd0qDMhFgiBg&label=CI%20iOS)](https://app.bitrise.io/app/70e79dc5-cae8-4cb7-a6cd-9a5bd3f3270f)
[![Bitrise Android](https://img.shields.io/bitrise/e4b6aade20ea9eb3?token=byZU0e1BJn_VYg2YuAs-cA&label=CI%20Android)](https://app.bitrise.io/app/e4b6aade20ea9eb3)
<BR>
[![OSS-Fuzz](https://oss-fuzz-build-logs.storage.googleapis.com/badges/pjsip.png)](https://oss-fuzz-build-logs.storage.googleapis.com/index.html#pjsip)
[![Coverity-Scan](https://scan.coverity.com/projects/905/badge.svg)](https://scan.coverity.com/projects/pjsip)
[![CodeQL](https://github.com/pjsip/pjproject/actions/workflows/codeql-analysis.yml/badge.svg?branch=master)](https://github.com/pjsip/pjproject/actions/workflows/codeql-analysis.yml)
[![docs.pjsip.org](https://readthedocs.org/projects/pjsip/badge/?version=latest)](https://docs.pjsip.org/en/latest/)


# PJSIP

PJSIPは、C言語で書かれた無料のオープンソース・マルチメディア通信ライブラリです。高レベルAPIをC、C++、Java、C#、Pythonで提供します。SIP、SDP、RTP、STUN、TURN、ICEといった標準準拠のプロトコルを実装しています。シグナリングプロトコル（SIP）に、豊富なマルチメディアフレームワークとNAT越え機能を組み合わせ、移植性の高い高レベルAPIとして提供します。デスクトップ、組み込みシステム、モバイル端末まで、ほぼあらゆる種類のシステムに適しています。

## PJSIPの入手

- メインリポジトリ: https://github.com/pjsip/pjproject
- リリース: https://github.com/pjsip/pjproject/releases


## ドキュメント

ドキュメントサイト: https://docs.pjsip.org

目次:

- 概要
  - [概要](https://docs.pjsip.org/en/latest/overview/intro.html)
  - [機能（データシート）](https://docs.pjsip.org/en/latest/overview/features.html)
  - [ライセンス](https://docs.pjsip.org/en/latest/overview/license.html)
- **はじめに**
  - [PJSIPの入手](https://docs.pjsip.org/en/latest/get-started/getting.html)
  - [一般的なガイドライン](https://docs.pjsip.org/en/latest/get-started/general_guidelines.html)
  - [Android](https://docs.pjsip.org/en/latest/get-started/android/index.html)
  - [iPhone](https://docs.pjsip.org/en/latest/get-started/ios/index.html)
  - [Mac/Linux/Unix](https://docs.pjsip.org/en/latest/get-started/posix/index.html)
  - [Windows](https://docs.pjsip.org/en/latest/get-started/windows/index.html)
  - [Windows Phone](https://docs.pjsip.org/en/latest/get-started/windows-phone/index.html)
- PJSUA2 - 高レベルAPIガイド
  - [はじめに](https://docs.pjsip.org/en/latest/pjsua2/intro.html)
  - [PJSUA2のビルド](https://docs.pjsip.org/en/latest/pjsua2/building.html)
  - [基本概念](https://docs.pjsip.org/en/latest/pjsua2/general_concept.html)
  - [Hello world!](https://docs.pjsip.org/en/latest/pjsua2/building.html)
  - [PJSUA2の使い方](https://docs.pjsip.org/en/latest/pjsua2/using/index.html)
  - [サンプルアプリケーション](https://docs.pjsip.org/en/latest/pjsua2/samples.html)
- 個別ガイド
  - [オーディオ](https://docs.pjsip.org/en/latest/specific-guides/index.html#audio)
  - [オーディオのトラブルシューティング](https://docs.pjsip.org/en/latest/specific-guides/index.html#audio-troubleshooting)
  - [ビルドと統合](https://docs.pjsip.org/en/latest/specific-guides/index.html#build-integration)
  - [開発とプログラミング](https://docs.pjsip.org/en/latest/specific-guides/index.html#development-programming)
  - [メディア](https://docs.pjsip.org/en/latest/specific-guides/index.html#media)
  - [ネットワークとNAT](https://docs.pjsip.org/en/latest/specific-guides/index.html#network-nat)
  - [性能とフットプリント](https://docs.pjsip.org/en/latest/specific-guides/index.html#performance-footprint)
  - [セキュリティ](https://docs.pjsip.org/en/latest/specific-guides/index.html#security)
  - [SIP](https://docs.pjsip.org/en/latest/specific-guides/index.html#sip)
  - [ビデオ](https://docs.pjsip.org/en/latest/specific-guides/index.html#video)
  - [その他](https://docs.pjsip.org/en/latest/specific-guides/index.html#other)
- APIリファレンス
  - [PJSUA2](https://docs.pjsip.org/en/latest/api/pjsua2/index.html) - 高レベルAPI（Java/C#/Python/C++/swig）
  - [PJSUA-LIB](https://docs.pjsip.org/en/latest/api/pjsua-lib/index.html) - 高レベルAPI（C）
  - [PJSIP](https://docs.pjsip.org/en/latest/api/pjsip/index.html) - SIPスタック
  - [PJMEDIA](https://docs.pjsip.org/en/latest/api/pjmedia/index.html) - メディアフレームワーク
  - [PJNATH](https://docs.pjsip.org/en/latest/api/pjnath/index.html) - NAT越え支援
  - [PJLIB-UTIL](https://docs.pjsip.org/en/latest/api/pjlib-util/index.html) - ユーティリティ
  - [PJLIB](https://docs.pjsip.org/en/latest/api/pjlib/index.html) - ポータブルライブラリ
