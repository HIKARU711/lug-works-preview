# Lug Works Production Site v0

> 作成日: 2026-06-12

Lug Worksコーポレートサイトの実装版 v0。

## 方針

- 依存なしの静的HTMLとして実装
- モック `mockups/a-plus-calm-partner/` を元に本番用メタ情報を追加
- `ai-fusion` 本体を公開せず、この `site/` のみを公開対象にする

## 公開対象

- `index.html`
- `assets/hero-implementation-collage.png`
- `robots.txt`
- `_headers`
- `favicon.svg`
- `site.webmanifest`

## 内部メモ

- `CONTACT_SETUP.md`
- 問い合わせフォームUIは実装済み。ただし正式な送信先/メールアドレスが決まるまで送信ボタンは無効化する。
- 現在の `canonical` / `og:url` / `og:image` / `twitter:image` / `site.webmanifest` は一時共有URL `https://ruai-dev.github.io/lug-works-preview/` 向け。正式ドメイン公開時に差し替える。

## 次にやること

1. フォーム送信先を決める
2. OGP画像を正式化する
3. ドメイン/メールアドレスを決める
4. 必要ならAstro/Tailwindへ移行する
