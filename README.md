# Simple HTML Previewer

ブラウザ上で動作する、環境構築不要の軽量なHTMLエディタ＆リアルタイムプレビューアーです。  
ランディングページ（LP）は[デジタル庁デザインシステム](https://design.digital.go.jp/)のガイドラインを参考に、クリーンでアクセシビリティの高い、エンジニア向けのデザインを採用しています。

## ✨ 特徴 (Features)

- **リアルタイムプレビュー**: 左側のエディタにHTMLを入力すると、右側の画面に瞬時に結果が反映されます。
- **ファイルエクスポート**: 作成したコードを `HTMLファイル` としてワンクリックでダウンロード可能（`<title>`タグからファイル名を自動推測）。
- **PDF出力機能**: プレビュー画面だけをターゲットにして、PDFとして印刷・保存できます。
- **柔軟なUIレイアウト**: ドラッグによる画面分割の調整や、プレビュー画面のみの全画面表示モードに対応。
- **ローカル完結**: サーバーとの通信を行わないため、セキュアかつ高速に動作します。LocalStorageを利用し、リロードしてもコードを保持します。

## 🚀 デモ (Demo)

**[https://github.com/dir-kakizawa/offline-report-toolkit/]**

## 📁 ファイル構成 (File Structure)

```text
.
├── index.html        # ランディングページ (LP)
├── previewer.html    # HTMLプレビューアー本体
├── prompt.md         # デジタル庁のデザインガイド準拠HTMLレポート生成プロンプト
└── README.md         # 本ファイル
```

## 🛠 使い方 (Usage)

本ツールはフロントエンド（HTML/CSS/JavaScript）のみで構築されているため、Node.jsなどの環境構築やビルドは一切不要です。

### ローカル環境での使用

1. 本リポジトリをクローン、またはZIPでダウンロードします。
2. フォルダ内の `previewer.html` をお好みのブラウザ（Chrome, Edge, Safari等）で直接開きます。
3. 生成AIが出力したHTMLをコピペしてプレビューします。

## 💻 使用技術 (Tech Stack)

- **HTML5**
- **CSS3** (CSS Variables, Flexbox, Grid, 外部CSSフレームワーク非依存)
- **Vanilla JavaScript** (外部ライブラリ非依存)

## 📄 ライセンス (License)

[MIT License](LICENSE)
