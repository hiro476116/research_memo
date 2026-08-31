# research_memo

研究・ゼミ用に作成した数理系のメモと発表資料を管理するリポジトリです。

## ディレクトリ構成

### `ラフパス/`

ラフパス理論の導入をまとめた文書です.

- `ラフパス.tex`: 本文と Appendix を含む LaTeX 原稿
- `ラフパス.pdf`: コンパイル済みPDF
- `.latexmkrc`: LuaLaTeX を使用するための設定


### `拡散モデルまとめ/`

拡散モデルと関連する確率解析・収束解析の資料をまとめています.

## ラフパス資料のコンパイル

LuaLaTeX と `latexmk` が利用できる環境で、次を実行します。

```sh
cd ラフパス
latexmk ラフパス.tex
```

`.aux`、`.log`、`.fls`、`.fdb_latexmk`、`.out`、`.synctex.gz`、`.dvi` は LaTeX のコンパイル時に生成される補助ファイルです。
