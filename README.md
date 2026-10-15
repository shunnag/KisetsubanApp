# 季節バン（Kisetsuban）

季節バンは、エアロハス対応の家庭用サーバー「KisetsubanServer」と組み合わせて使う、Mac用のメニューバーアプリです。季節の番人として、エアコンの運転状況と温度をメニューバーに表示します。また、近くにあるSwitchBot温湿度計の温度と湿度をBluetoothで受信して、サーバーに送信します。

このリポジトリには、配布用のアプリとアップデート情報だけを置いています。

## 主な機能

- メニューバーに運転状況と設定温度または室温を表示します。Optionキーを押しながらクリックすると、詳しい情報を表示します。
- 近くにあるSwitchBot温湿度計の温度と湿度をBluetoothで受信して、サーバーに送信します。
- 新しいバージョンを自動的に確認して、アップデートできます。
- 日本語と英語に対応しています。

## 動作環境

- Appleシリコンを搭載したMac
- macOS 26以降
- 同じネットワーク上で動作するKisetsubanServer（公開準備中）

## インストール

1. [Releases](https://github.com/shunnag/KisetsubanApp/releases/latest)から最新のzipをダウンロードして開きます。
2. 季節バン（Kisetsuban.app）を「アプリケーション」フォルダに移動して開きます。
3. メニューバーの季節バン＞「設定…」で、サーバーのURLを入力します。Bluetoothで受信する場合は、「Bluetooth受信」をオンにして、サーバーの管理画面で発行したペアリングコードを入力します。

アプリはApple Developer IDで署名され、Appleの公証を受けています。以降のアップデートは、アプリ内で自動的に確認されます。

## 注意事項

「エアロハス」はパナソニック ホームズ株式会社の登録商標です。「SwitchBot」は Woan Technology (Shenzhen) Co., Ltd. の登録商標です。季節バン（Kisetsuban）は個人が制作した非公式のファンメイドのサポートアプリです。パナソニック ホームズ株式会社をはじめとするパナソニックグループ各社、および Woan Technology (Shenzhen) Co., Ltd. をはじめとする SwitchBot 関連各社の公式製品ではなく、各社とは一切関係がなく、承認・提携・後援を受けたものではありません。ご利用は自己責任でお願いします。

---

# Kisetsuban

Kisetsuban is a menu bar companion for KisetsubanServer, a home server for Airlohas whole-house air conditioning. It shows the air conditioner’s status and temperature in the menu bar, and it can receive temperature and humidity from nearby SwitchBot sensors over Bluetooth and send them to the server.

This repository hosts signed and notarized releases and the update feed only.

## Requirements

- A Mac with Apple silicon
- macOS 26 or later
- KisetsubanServer on the same network (coming soon)

## Installation

1. Download the latest zip from [Releases](https://github.com/shunnag/KisetsubanApp/releases/latest) and open it.
2. Move Kisetsuban to the Applications folder and open it.
3. Choose Settings… from the Kisetsuban menu and enter the server URL. To receive Bluetooth sensors, turn on Bluetooth Reception and enter a pairing code from the server’s admin page.

Kisetsuban is signed with an Apple Developer ID and notarized by Apple. It checks for updates automatically.

## Notice

エアロハス (Airlohas) is a registered trademark of Panasonic Homes Co., Ltd. SwitchBot is a registered trademark of Woan Technology (Shenzhen) Co., Ltd. Kisetsuban is an unofficial, fan-made support app created by an individual. It is not an official product of, and is not affiliated with, endorsed, sponsored or approved by, Panasonic Homes Co., Ltd. or any other Panasonic Group company, or Woan Technology (Shenzhen) Co., Ltd. or any of its affiliates. Use at your own risk.
