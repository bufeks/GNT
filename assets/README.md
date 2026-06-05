# assets — 画像・PDF素材

企画書（`index.html`）で使う画像・PDFを置く場所です。

## 置き方（重要）

`index.html` は画像を **`assets/` 直下** で参照しています（例：`assets/asset_engawa_bench.jpg`）。
そのため **画像は `assets/` の直下に置いてください**（サブフォルダに入れると参照が切れます）。

```
assets/
├── asset_xxx.jpg      # 企画書で使う画像はすべてここ（直下）
├── engawa_ref_xx.jpg
├── floor_plan_0604.png
└── pdf/                # PDFのみサブフォルダにまとめる
```

- ファイル名は **半角英数・ハイフン/アンダースコア** 推奨。
- HTML からの参照例：`<img src="assets/asset_engawa_bench.jpg">`

## よくある間違い

- ❌ `assets/images/xxx.jpg` に置く → HTMLは `assets/xxx.jpg` を見るため表示されません。
- ✅ `assets/xxx.jpg` に置く。

> GitHub の Web からアップする場合は、`assets` フォルダを開いた状態で **Add file → Upload files** してください。
