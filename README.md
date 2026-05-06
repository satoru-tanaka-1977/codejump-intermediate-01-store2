# Furniture Design（複数ページ構成・ECサイト模写）

CodeJump中級編の課題として、家具ECサイトを再現実装しました。
複数ページ構成とjQueryを使ったハンバーガーメニューの実装、CSSグリッドレイアウトの理解を目的としています。

---

## 使用技術

- HTML5
- CSS3（Flexbox / CSS Grid）
- JavaScript / jQuery
- レスポンシブ対応（@media screen and (max-width: 900px)）

---

## 実装内容

- 複数ページ構成（index / products / item1〜16 / about / company）
- jQueryを使ったハンバーガーメニューの実装（addClass / removeClass）
- `.open`クラスの付け外しによるメニュー開閉アニメーション
- CSS Gridを使った商品一覧レイアウト（4列 / SP時2列）
- ページネーションの実装
- `position: fixed`によるヘッダー固定
- `position: absolute`によるフッターの画面下固定

---

## 学んだこと

- 複数ページ構成でのaタグによるページ遷移の実装を実践できた
- jQueryの`hasClass` / `addClass` / `removeClass`の使い方を復習できた
- `.open`クラスがある・なしでCSSを切り替える設計を理解した
- ハンバーガーメニューのアニメーション（translateY / rotate）を習得した
- CSS Gridの`grid-template-columns`と`gap`の使い方を理解した

---

## 感想

ハンバーガーメニューの実装は初めてで、特に`.open`クラスのあるなしでCSSを切り替える設計や、メニューボタンのアニメーションが難しかったが、プロゲートで習ったjQueryの知識を復習しながら自力で書くことができた。

複数ページ構成の実装を通じて、aタグによるページ遷移の考え方や、共通CSSの設計力も身についてきたと感じる。

---

## 公開URL

👉 https://satoru-tanaka-1977.github.io/codejump-intermediate-01-store2/