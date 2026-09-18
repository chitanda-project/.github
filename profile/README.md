<div align="center">

# 🌸 千反田 / Chitanda Project

**次世代プロキシ・ルーティングエンジンおよびクライアントエコシステム**

[![Official Website](https://img.shields.io/badge/Official-chitanda.net-blue?style=for-the-badge&logo=google-chrome&logoColor=white)](https://chitanda.net)
[![License](https://img.shields.io/badge/License-GPL--3.0%20%2F%20MIT-green?style=for-the-badge)](https://github.com/chitanda-project)
[![Tech Stack](https://img.shields.io/badge/Stack-Go%20%7C%20Kotlin%20%7C%20Lua-9cf?style=for-the-badge)](https://github.com/chitanda-project)

<p align="center">
高速で安定した透過的プロキシ、柔軟なインテリジェントルーティング、安全な暗号化トンネリングを提供します。
</p>

</div>

> [!WARNING]
> ### ⚠️ 免責事項 (Disclaimer)
> 本組織が公開・提供しているすべてのプロジェクトおよび関連リソースは、学術研究、ネットワークセキュリティ検証、および正当な管理運用を目的としています。
> 
> 1. **法令遵守の義務**：本プロジェクトのコードや関連ソフトウェアを利用する際は、**必ずご利用者ご自身の所在国・地域の法令および規則を遵守してください**。
> 2. **利用の禁止**：本プロジェクトの利用が所在国または地域の法律・規制に違反する場合、**いかなる目的であっても本ソフトウェアのダウンロード、インストール、実行、および二次配布を行わないでください**。
> 3. **免責条項**：開発者およびプロジェクト保守管理者は、本プロジェクトの使用、誤用、またはそれに関連して生じたいかなる損害や法的紛争・責任についても一切の責任を負いません。

---

### 📦 主要コンポーネント & エコシステム

`
┌─────────────────────────────────────────────────────────────┐
│                   Chitanda Core (Engine)                    │
│           Xray-core & Mihomo High-Performance Core           │
└──────────────────────────────┬──────────────────────────────┘
                               │
              ┌────────────────┴────────────────┐
              ▼                                 ▼
┌───────────────────────────┐     ┌───────────────────────────┐
│   Chitanda for Android    │     │   Chitanda for OpenClash  │
│   (CMFA Client - Kotlin)  │     │   (Router Client - Lua)   │
└───────────────────────────┘     └───────────────────────────┘
`

- 🚀 **[Chitanda Core（コアエンジン）](https://github.com/chitanda-project/chitanda)**  
  Xray-core と Mihomo を統合した次世代プロキシコア。高度なパケットルーティングとゼロコピーパイプによる超高スループットを実現。

- 📱 **[Chitanda for Android（CMFA）](https://github.com/chitanda-project/chitanda-cmfa)**  
  Chitanda Core を内蔵した、直感的かつパワフルな Android 向けプロキシクライアント。

- 🌐 **[Chitanda for OpenClash](https://github.com/chitanda-project/chitanda-openclash)**  
  家庭用ルーターやゲートウェイ環境（OpenWrt / iStoreOS）に Chitanda Core を最適化統合したソリューション。

- 📖 **[ドキュメント / 公式ポータル](https://chitanda.net)**  
  利用ガイド、設定リファレンス、およびリリース案内。

---

### 🚀 リポジトリステータス

| プロジェクト | プラットフォーム | 最新リリース | CI / ビルドステータス |
| :--- | :--- | :--- | :--- |
| **Chitanda Core** | Linux / Windows / macOS / Android | [![Release](https://img.shields.io/github/v/release/chitanda-project/chitanda?color=blue&style=flat-square)](https://github.com/chitanda-project/chitanda/releases) | [![Build](https://github.com/chitanda-project/chitanda/actions/workflows/release.yml/badge.svg)](https://github.com/chitanda-project/chitanda/actions) |
| **Chitanda CMFA** | Android | [![Release](https://img.shields.io/github/v/release/chitanda-project/chitanda-cmfa?color=green&style=flat-square)](https://github.com/chitanda-project/chitanda-cmfa/releases) | [![Build](https://github.com/chitanda-project/chitanda-cmfa/actions/workflows/build-release.yaml/badge.svg)](https://github.com/chitanda-project/chitanda-cmfa/actions) |
| **Chitanda OpenClash** | OpenWrt / Linux Router | [![Release](https://img.shields.io/github/v/release/chitanda-project/chitanda-openclash?color=orange&style=flat-square)](https://github.com/chitanda-project/chitanda-openclash/releases) | [![CI](https://github.com/chitanda-project/chitanda-openclash/actions/workflows/chitanda-core-verify.yml/badge.svg)](https://github.com/chitanda-project/chitanda-openclash/actions) |

---

<div align="center">
  <sub>各コンポーネントはそれぞれのオープンソースライセンス（GPL-3.0 / MIT）に基づいて提供されています。</sub>
</div>