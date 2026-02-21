# mac-snip-tool
マック用の簡易スニッピングツール v1.0

## GitHub Release 版の使い方

GitHub Release で配布する `Snipmac_and_start_app.zip` を使って起動できます。
### ダウンロードURL
- Release ページ: `https://github.com/hirotaka-murakami/mac-snip-tool/releases/tag/v1.0`
- 直接ダウンロード (ZIP): `https://github.com/hirotaka-murakami/mac-snip-tool/archive/refs/tags/v1.0.zip`

### 1. ZIP を解凍する
- `Snipmac_and_start_app.zip` をダウンロードして解凍してください。

### 2. ファイル配置を確認する
解凍後、以下のファイルがあるか確認してください

- `Snipmac.app`

## 3. 初回起動で必要な macOS 設定

`システム設定 -> プライバシーとセキュリティ -> 画面収録とシステムオーディオ録音`

- `Snipmac` を ON

### 4. 起動する
ターミナルで上記 2 ファイルがあるフォルダに移動し、以下を実行してください。



## 基本的な使い方

- `start_app.sh` 実行後、`Snipmac.app` が起動します。
- `Snipmac.app` は直接起動でも動作します。
- 画面上でキャプチャ範囲を選択してスニップできます。
- 初回起動時に macOS の権限（画面収録など）が必要な場合は許可してください。

## ログイン時に自動起動する設定（任意）

`Snipmac.app` は、macOS の「ログイン項目」に追加すると自動起動できます。

1. `システム設定` を開く
2. `一般` -> `ログイン項目と機能拡張` を開く
3. `ログイン時に開く` に `Snipmac.app` を追加する

次回ログイン以降、`Snipmac.app` が自動で起動します。

