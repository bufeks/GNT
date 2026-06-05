# GNT｜中目黒 新店 開業計画

Good Neighbors Tokyo が中目黒にオープンする自社飲食店の計画・紹介ページをまとめるリポジトリです。
公開ページは **1ページのWebサイト（`index.html`）** として作成し、GitHub Pages で関係者に共有します。

## 公開ページ（GitHub Pages）

公開URL（Pages 有効化後）:

```
https://bufeks.github.io/gnt/
```

> 関係者はこのURLを開くだけで閲覧できます（GitHubアカウント不要）。

### 初回のみ：GitHub Pages を有効化する手順

1. GitHub のリポジトリ `bufeks/gnt` を開く
2. **Settings → Pages** を開く
3. **Build and deployment → Source** で **Deploy from a branch** を選択
4. **Branch** を `main` ／ フォルダを `/ (root)` にして **Save**
5. 数分後、上記URLで公開されます

※ `main` を公開元にする想定です。編集はブランチ＋Pull Request で行い、`main` にマージすると公開ページに反映されます。

## バージョン管理

公開ページの各バージョンを `versions/` に保存しています。`index.html` は常に最新版で、過去の版に戻したいときは `versions/` のファイルを `index.html` に戻します。

| 版 | 日付 | ファイル | 備考 |
|----|------|----------|------|
| v1 | 2026-06-05 | `versions/index-v1-20260605.html` | ベース版（GOOD NEIGHBORS TOKYO — 縁を、ひらく。） |

> 版を更新したら `versions/index-vN-YYYYMMDD.html` として新しいファイルを追加し、この表に1行足してください。git の履歴でも全変更を追えます。

## 編集方法

- 公開内容は `index.html`（HTML＋CSS）に含まれています。
- GitHub の Web 上でも `index.html` を直接編集できます（ファイルを開いて鉛筆アイコン）。
- 大きめの改訂をしたら、その時点の `index.html` を `versions/` にコピーして版として残してください。

## 構成

```
.
├── index.html                       # 公開ページ本体（最新版・これが公開される）
├── versions/                        # 過去〜各時点のバージョン保管
│   └── index-v1-20260605.html       # v1 ベース版
└── README.md                        # このファイル（運用メモ）
```
