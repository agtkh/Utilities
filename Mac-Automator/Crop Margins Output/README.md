# PDF Crop Margins Print Plugin for Mac

MacのプリントダイアログからPDFの余白を自動除去するAutomatorプラグイン。

![./usage.gif](./usage.gif)
## 前提条件

本プラグインの利用には以下のツールが必要である。

**1. Ghostscript**
PDF処理用ライブラリ。

```bash
brew install ghostscript

```

**2. pdf-crop-margins**
余白除去を行うPythonツール。

```bash
pip install pdf-crop-margins

```
## ダウンロード

[https://github.com/agtkh/Utilities/raw/refs/heads/main/Mac-Automator/Crop%20Margins%20Output/Crop%20Margins%20Output.workflow.zip](https://github.com/agtkh/Utilities/raw/refs/heads/main/Mac-Automator/Crop%20Margins%20Output/Crop%20Margins%20Output.workflow.zip)

## インストール

ダウンロードしたZIPファイルを解凍し、 `.workflow` ファイルを以下のディレクトリに配置する。

`~/Library/PDF Services`

※ディレクトリが存在しない場合は作成すること。

## 使用方法

1. 任意のドキュメントで印刷画面（`Command + P`）を開く。
2. ダイアログ下部の「PDF」プルダウンメニューから本プラグインを選択する。
3. 保存先を指定する。
4. 処理完了後、通知が表示される