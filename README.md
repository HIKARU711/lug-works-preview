# A+ Calm Partner Mock

> 作成日: 2026-06-10

Figma MCPのStarterプラン呼び出し上限に到達したため、同じ方針をローカルHTMLモックとして作成。

## コンセプト

**Calm Partner + Quiet Proof + Clear Entry**

- A案の静かな信頼感を維持
- Proof / Works を追加
- Pricing / Contact を明確化
- Hero右側を `AI Implementation Map` として作り込み

## 2026-06-11 更新

Hikaruから「シンプルすぎると、しょぼく見えるのではないか」という懸念が出たため、見た目を上質化。

変更方針:

- Heroを単なるカードではなく、診断レポート/コード/導線マップ/改善メモのレイヤー構成に変更
- `Straightforward Brand Guidelines` 的なブランド母艦感を追加
- `Sincere Professional Legal Services` 的な信頼感と説明階層を追加
- `Sophisticated Vacation House Rental` 的な余白と上質感を少し追加
- PricingをSaaSカードではなく相談メニューとして再構成

判断:

- 旧版は構成確認用としてはOKだが、本番サイトの印象としては弱い
- 新版は「AI実装パートナーとしての制作力」を第一印象で見せる方向

## 2026-06-11 追加修正

Hikaruから「生成画像はいいが、実際のブラウザ表示は違って見える」と指摘。

対応:

- Hero右側のCSS疑似図形をやめ、生成した実ビジュアル素材を配置
- 素材: `assets/hero-implementation-collage.png`
- ブラウザ上でも、診断レポート/AI活用設計/導線マップ/改善提案メモの質感が出るように変更

判断:

- 画像コンセプトとブラウザ表示の差は、CSS図形で紙・写真・レポートの質感を再現しようとしたことが主因
- 本番でもHeroやProofには、CSSだけでなく実ビジュアル素材を使う方がよい

## 表示方法

`index.html` をブラウザで開く。

## 次アクション

1. Hikaruが見た目を確認する。
2. 必要なら文言/構成/密度を調整する。
3. Figma MCP上限が戻ったら、HTMLをFigmaに取り込むか、採用デザインとして実コード化する。
