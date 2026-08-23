<p align="center"><img src="./assets/banner.svg" alt="XXD Panel 054 project banner" width="1200"></p>

<div align="center">

# 🦁 XXD Panel 054

### 一つの記憶を主役と不均等な六つの断片に分ける

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)
[![Modes](https://img.shields.io/badge/Modes-4-EF805E?style=flat-square)](#)
[![Output](https://img.shields.io/badge/Output-PNG-4AA1AE?style=flat-square)](#)

<a href="README.md">简体中文</a> 選択的記憶 · 主役 · 六枚のステッカー · マット印刷 · 空気感のある青

写真を物語の主役一つと、大きさと重要度が異なる正確に六枚の記憶ステッカーへ圧縮します。マットなガッシュ、切り紙、リソグラフ、シルクスクリーンの質感で、アイコン目録ではなく静かな独立出版の収集ページにします。

## この Skill が必要な理由

このスタイルは元写真に依存し、内容を差し替えられる装飾プリセットではありません。変換は次の因果鎖に従います：

```text
lock identity, silhouette, posture, and relation → preserve three cues → compress into three to six large shapes → build one main visual → select exactly six source-specific fragments → vary sticker scale, angle, overlap, and hierarchy → unify matte gouache and print texture → retain airy blue whitespace → add minimal copy
```

無関係な写真に替えても主役、六つの断片、形、階層、色、間隔、文案が実質的に変わらないなら、本 Panel の成果ではありません。

## ビジュアル契約

- シルエット、比率、姿勢、動作、構造、色、素材、関係から元写真固有の手掛かりを三つ以上保つ。
- 三〜六個の大きな形で明確な主役を作り、元写真に根拠のある記憶断片を正確に六つ選ぶ。
- 六枚は大きさと重要度を変え、非対称に回転、重なり、はみ出しを用いる。目録、六分割、同寸アイコンにはしない。
- 主役とステッカーをマットなガッシュ、切り紙、リソグラフ、シルクスクリーンで統一し、空気感のある青、淡い中性色、ごく少量のくすみピンクを使う。
- 尺度差、正負形、重なり、広い静かな地で焦点を一つに保つ。

完全な美的制約と拒否項目は Skill と生成プロンプトにあります。原文の美的動機を守りつつ、歴史的な3:4画布を隠れた既定値にはしません。 [SKILL.md](SKILL.md) · [production prompt](references/xxd-panel-054-prompt.en.md)

## 作例 · X より

> [小小東（@xiaoxiaodong01）](https://x.com/xiaoxiaodong01/status/2091539410533691899) · 2026年8月23日<br>
> GPT2 × ステッカー × 古物感 × 視覚的手掛かり × 美学プロンプト × VOL.054

<table>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091539410533691899"><img src="./assets/examples/sample-01.jpg" alt="XXD Panel 054 作例 1"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091539410533691899"><img src="./assets/examples/sample-02.jpg" alt="XXD Panel 054 作例 2"></a></td>
  </tr>
</table>

<p align="center"><a href="https://x.com/xiaoxiaodong01/status/2091539410533691899">元の投稿と完全なプロンプトを見る →</a></p>

これらの作例は 054 の美的意図を示すものであり、作例の被写体、構図、配色、コピー、旧キャンバス比率が生成時の参照や現在の既定値になることはありません。

## 組み合わせ可能な4つの出力

`1`、`1+3`、`1,2,4`、`全部` で一つまたは複数を選べます。`全部` は元写真1枚につき通常3点と壁紙4点、計7点のPNGを出力します。

| モード | 未指定時の寸法 | 成果物 |
| --- | --- | --- |
| `top-bottom` | 元画像適応 `W×2H` | 上に完全な元写真、下に変換デザイン、厳密な50/50 |
| `left-right` | 元画像適応 `2W×H` | 左に完全な元写真、右に変換デザイン、厳密な50/50 |
| `design-only` | 元画像適応 `W×H` | 変換デザインのみ。元写真は表示しない |
| `wallpaper-pack` | 端末別に指定 | スマートフォン、iPad、デスクトップ、子ども用ウォッチの個別PNG |

壁紙は連動または独立を選べます。連動は一つの基準作を承認し、全端末が元写真と同じ基準作を参照します。切り抜きも派生連鎖もしません。独立は各端末が元写真だけを参照します。

## 文案と言語

生成前に自動文案、正確な指定文案、文字なしを確定します。言語は指示文ではなく対象読者に従い、完成稿は一字一句保持します。

本プロジェクトの文案規則：主体、動作、環境、感情、音、記憶、文化的文脈に強く結びつく一語、短句、極短い題名だけを抽出し、余白、ステッカーの隙間、主役の縁に小さく軽く置きます。各ステッカーにはラベルを付けません。

## 幾何、ラスター、信頼

通常モードは指定がなければ元画像に適応し、二連は厳密な50/50、成果物はPNGラスターです。毎回 `~/Desktop/xxd/` に新規タスクを作り、非公開の生成経路情報を開示しません。

設定済みの画像ブリッジは匿名化された状態だけを返し、提供元、接続先、認証情報、ヘッダー、プロンプト、応答、アカウント情報を開示しません。SVG、HTML、Canvas、図解、プログラム描画は最終ラスター作品の代替になりません。

## 使い始める

```bash
git clone https://github.com/nevertoday/xxd-panel-054.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-054" ~/.codex/skills/xxd-panel-054
```

Claude Code では同じフォルダを次へリンクできます： `~/.claude/skills/xxd-panel-054`. インストール後に Agent セッションを再起動してください。

```text
$xxd-panel-054
Use this photograph, ask me for the modes and copy setting, then generate fresh raster outputs.
```

完全仕様: [Skill ワークフロー](SKILL.md) · [原始スタイル資料](references/054-source.md) · [英語生成プロンプト](references/xxd-panel-054-prompt.en.md) · [中国語生成プロンプト](references/xxd-panel-054-prompt.zh-CN.md)

## XXD について

XXD は Xiaoxiaodong のブランド名略称です。作成・管理： [@xiaoxiaodong01](https://x.com/xiaoxiaodong01).

## サポートとメンバーシップ

### 個別コンサルティング · 299元／時間

Skills の使用とワークフローに関する一対一の相談です。WeChat で Xiaoxiaodong にご連絡ください。 [WeChat](https://xiaoxiaodong.pages.dev/assets/wechat-qr.png)

### Xiaoxiaodong Skills ユーザー交流グループ · 99元

一回の支払いで Skills ユーザー交流グループに参加できます。時間制の個別相談は別料金です。

### Knowledge Planet＋会員プロンプトライブラリ · 699元／年

Knowledge Planet と会員プロンプトライブラリは一つの年会です。どちらかで加入後、WeChat で連絡するともう一方も開通できます。

[Knowledge Planet](https://wx.zsxq.com/group/15554814142882) · [Member Prompt Library](https://vip.xiaoxiaodong.ai/)

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD WeChat" width="280"></a></p>

<div align="center"><strong>記憶は六つのアイコンではなく、強弱のある収集です。</strong></div>

---

<div align="center">

## ☕ オープンソースを支援

中国語圏以外では Buy Me a Coffee を利用できます。支援は任意で、オープンソースへのアクセスを変えません。


<p align="center"><a href="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true"><img src="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true" alt="Buy Me a Coffee" width="180"></a></p>

</div>
</div>
