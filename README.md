# DoMaTeX v0.1

DoMaTeXはMarkdown風記法でLaTeX文書を簡単に作成できるラッパーです。
本文だけに集中でき、スタイルや設定を再利用しやすく設計されています。

---

## 特徴

- Markdownライクな記法で直感的に記述可能
- 設定ファイルによるスタイルの再利用
- LaTeXネイティブ埋め込み可能（自己責任）
- 小さくシンプルで、v0.1では愚直な変換を行う

---

## 対象ユーザー

- LaTeXを使うが本文だけ書きたい人
- 論文やレポート作成など、LaTeXをメインに扱わない研究者・学生

---

## インストール

1. Racketを公式サイトからダウンロードしてインストールしてください:  
   [https://racket-lang.org/](https://racket-lang.org/)
2. LaTeX環境（lualatex + latexmk）が必要です  
   - ほとんどのLaTeXユーザーは既に導入済みです
3. DoMaTeXスクリプトをダウンロードしてください

---

## 使い方

```bash
racket domatex.rkt build example.md -c config.yaml

