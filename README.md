# Café Noir – Portfolio Piece

架空の自家焙煎スペシャルティコーヒー専門店「Café Noir」のWebサイトデザイン。

## 🎨 3 デザインバリエーション

エントリーポイント: [`index.html`](index.html)

| 版 | URL | コンセプト |
|---|---|---|
| 🅐 Editorial | [editorial.html](editorial.html) | 雑誌風・非対称・産地マーキー・大型セリフ |
| 🅑 Cinematic | [cinematic.html](cinematic.html) | 章立て・パララックス・没入型ストーリー |
| 🅒 Minimal 和モダン | [minimal.html](minimal.html) | 白基調・縦書き・漢数字・余白多め |

## 🛠 技術構成

- 純粋な HTML / CSS のみ（フレームワーク・ビルドツール不使用）
- レスポンシブ（PC / タブレット / スマートフォン対応）
- Google Fonts: Noto Serif JP / Noto Sans JP / Playfair Display / Cormorant Garamond / Shippori Mincho
- 写真素材: Unsplash（フリーライセンス）

## 📐 制作プロセス

1. 構成設計：カフェHPに必要なセクションを9つに整理（Hero / About / Story / Menu / Owner / Instagram / Access / Footer 等）
2. 1案目（v0 ベースライン）でレイアウトと配色を確立
3. 「もっとデザインを良くしたい」というディレクションから、3方向のバリエーションを並列で展開
4. クライアントの選択 → 🅑 Cinematic を本命として詰める
5. 写真とコピーの整合（タイトルに合う写真選び・写真に合うコピー再構成）
6. ディレクターズノートを店主紹介セクションへ格上げ

## 🎯 デザイン上のこだわり（Cinematic 版）

- **章立て構成** : CHAPTER 01 / 02 / 03 で物語性を演出
- **パララックス背景** : `background-attachment: fixed` で没入感
- **タイポグラフィ** : Cormorant Garamond イタリックで映画的余韻
- **メタデータ表示** : "08:14 AM JST · 35.6712°N · 139.7028°E" 等の映画的ディテール
- **クレジット風フッター** : "Cast / Music / Stage" 等で映画のスタッフロール感

## 🚀 デプロイ

GitHub Pages にて公開中。

## 📁 ファイル構成

```
├── index.html         # 比較用ランディング（A/B/C 選択）
├── editorial.html     # 🅐 Editorial 版
├── editorial.css
├── cinematic.html     # 🅑 Cinematic 版
├── cinematic.css
├── minimal.html       # 🅒 Minimal 和モダン版
├── minimal.css
├── v0.html            # ベースライン（v0）
├── styles.css         # v0 用CSS
└── images/            # 全14画像
```

---

© 2026 — Portfolio piece. Café Noir is a fictional brand.
