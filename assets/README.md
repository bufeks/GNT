# assets — 画像・PDF素材

企画書（`index.html`）やブリーフ（`source/brief.md`）で使う画像・PDFを置く場所です。

## 置き方

```
assets/
├── images/   # 写真・スクショ・パース画像（jpg / png / webp）
└── pdf/       # 配布・参照用PDF
```

- ファイル名は **半角英数・ハイフン** 推奨（日本語名でも動きますが、URL化の安全性のため英数を推奨）。
- HTML からは相対パスで参照します。例：`<img src="assets/images/facade.jpg">`

## ブリーフで参照している素材（アップ待ち）

`source/brief.md` で言及されている資料です。アップしていただけると、企画書に反映できます。

| 資料 | 内容 | 推奨ファイル名（例） | 状態 |
|------|------|----------------------|------|
| 資料B | GNT_ALL_251201_v2（過去コンセプト資料） | `assets/pdf/gnt-all-v2.pdf` | 未アップ |
| 資料C | ビギビル 1F商業イメージパース | `assets/pdf/facade-perspective.pdf` または `assets/images/facade-perspective.jpg` | 未アップ |
| 資料D | 平面構想スクショ | `assets/images/floor-plan.png` | 未アップ |
| ロゴ | GOOD NEIGHBORS TOKYO ロゴ | `assets/images/logo.svg` / `logo.png` | 未アップ |

> ファイル名はあくまで例です。実際の名前で置いていただければ、こちらでHTMLの参照を合わせます。
