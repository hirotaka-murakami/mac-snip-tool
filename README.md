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
- `nipmac.app_使い方と初回設定.md`

## 3. 初回起動で必要な macOS 設定

初回起動時は、以下の 2 つを設定してください。

### ② ブロックを解除する（初回のみ）

1. `システム設定` -> `プライバシーとセキュリティ` を開く
2. 下の方に `「Snipmacはブロックされました」` が表示される
3. `「このまま開く」` を押す

### ① 画面収録の権限を許可する

1. `システム設定` -> `プライバシーとセキュリティ` -> `画面収録とシステムオーディオ録音` を開く
2. `Snipmac` を ON にする

この操作は初回のみ必要です。以降は通常どおり起動できます。

## 基本的な使い方

- `Snipmac.app` を起動します。
- 画面上でキャプチャ範囲を選択してスニップできます。
- 初回起動時に macOS の権限（画面収録など）が必要な場合は許可してください。

## ログイン時に自動起動する設定（任意）

`Snipmac.app` は、macOS の「ログイン項目」に追加すると自動起動できます。

1. `システム設定` を開く
2. `一般` -> `ログイン項目と機能拡張` を開く
3. `ログイン時に開く` に `Snipmac.app` を追加する

次回ログイン以降、`Snipmac.app` が自動で起動します。

