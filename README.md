# Toolbox

暮らしに役立つ無料の計算ツール集（静的サイト）。GitHub Pages で公開し、SEO 経由の流入を広告・アフィリエイトで収益化することを目指す「スモールベット」プロジェクト。

## 公開URL

https://gerogeromaru.github.io/toolbox/

## 収録ツール

- 年収手取り計算ツール（`/take-home/`）

## 構成

```
toolbox/
├─ index.html          # ツール一覧（ランディング）
├─ take-home/          # 手取り計算ツール
├─ privacy/            # プライバシーポリシー（AdSense審査に必要）
├─ assets/style.css    # 共通スタイル
├─ robots.txt
└─ sitemap.xml
```

## ローカル確認

```powershell
python -m http.server 8000
# ブラウザで http://localhost:8000/ を開く
```

## ツールの増やし方

1. 新しいフォルダ（例 `word-count/`）を作り `index.html` を置く
2. `index.html`（一覧）にリンクを追加
3. `sitemap.xml` に URL を追加
4. commit して push（GitHub Pages に自動反映）

## 収益化メモ

- Google AdSense は「独自コンテンツ＋一定の流入＋プライバシーポリシー」が審査の前提。まずツールを増やしてアクセスを育てる。
- 各ページの `<!-- AdSense -->` 箇所に審査通過後のコードを貼る。
