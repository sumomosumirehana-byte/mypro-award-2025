# マイプロアワード2025 受賞作品LP — Claude Code 引き継ぎドキュメント

## プロジェクト概要

明蓬館高等学校「マイプロアワード2025」受賞作品18点を紹介するランディングページ（LP）の制作。  
Google DriveのSVG形式QRコードから作品原本リンクを自動抽出し、PDFの審査員講評を加えてWebページ化した。

---

## 完成済みファイル

- **`award_winners.html`**（このフォルダに同梱）
  - 全18作品掲載済み
  - カテゴリフィルター機能付き
  - スクロールアニメーション付き
  - 明蓬館ブランドカラー適用済み

---

## ブランドガイドライン（明蓬館高等学校）

```css
--bg:           #f4f7f0   /* ページ背景・薄いグリーン */
--primary:      #231815   /* テキスト・ほぼ黒 */
--green-light:  #AACE36   /* アクセント・黄緑 */
--green-mid:    #18943B   /* メイングリーン */
--green-dark:   #128132   /* ダークグリーン */
```

ロゴSVGファイル：`logo.svg`（同梱）  
フォント：Noto Serif JP / Cormorant Garamond（Google Fonts）

---

## 作品データ一覧（全18件）

### 課題解決型

| タイトル | 賞 | Drive URL |
|---|---|---|
| 飲食店（カフェ）探検隊２！！！！ | 最優秀賞 | https://drive.google.com/file/d/1DKOE2IzG5DRvx9WHejuVFKOEVtp0jBzT/view?usp=sharing |
| 写真が上手くなるには | 優秀賞 | https://drive.google.com/file/d/1oMIbqIyrqhkNNmUfoxmxOKunJjx4w-rA/view?usp=sharing |
| 就職先が決まるまで | 審査員特別賞 | https://drive.google.com/file/d/1ZIJ8oVkNt1Nn4TDXTIRun8LKCSMeMvdz/view?usp=sharing |

### 創造型

| タイトル | 賞 | Drive URL |
|---|---|---|
| 練り切りづくり | 最優秀賞 | https://drive.google.com/file/d/1FKCmyxjPRCl7uOdd1nZfsGe65pOg1jc7/view?usp=sharing |
| スクリーン７ G-0 | 優秀賞 | https://drive.google.com/file/d/1aaFqKHTYZ6iT9GhyxHxAa7rbdYQEfVS9/view?usp=sharing |

### 知的発見型

| タイトル | 賞 | Drive URL |
|---|---|---|
| 『そして誰もいなくなった』オマージュ作品リスト | 最優秀賞 | https://drive.google.com/file/d/1VorVgFzz68Z401IA40xklhBcUY_FezSW/view?usp=sharing |
| アリの生態研究〜全滅まで〜 | 優秀賞 | https://drive.google.com/file/d/1cmr3daZ0PBwXAv8hSfSoZOPlASSvRiNd/view?usp=sharing |
| 高校数学から見る群論の面白さ | 審査員特別賞 | https://drive.google.com/file/d/18bUlH_YTdVxMn7U2ycS-QIoUOZ5G-iBi/view?usp=sharing |

### 教科推薦

| タイトル | 教科 | Drive URL |
|---|---|---|
| 見る、知る、学ぶ。桜と文学・桜と古典芸能 | 国語科（言語文化） | https://drive.google.com/file/d/1nQ8uD13HeZxlnEqWwO2JaL5xtJmJrPuv/view?usp=sharing |
| 三角関数を和算の角度から調べて実際に試行してみた | 数学科（数学Ⅰ） | https://drive.google.com/file/d/12p4jP387uM7JtpX_2V_IlnbdfvE3AVoO/view?usp=sharing |
| Sky Mapping ― 空撮が切り開く新たな地理探究― | 地歴科（地理総合） | https://drive.google.com/file/d/1F2L6IO_WdGMin_RSaf4vWUoy97jPT0Ij/view?usp=sharing |
| 物価高でも子ども食堂の食材と笑顔は絶やさない | 公民科（政治・経済） | https://drive.google.com/file/d/1sy5gPwVlYLZc-EBurHCgrCs3gSj0kdxW/view?usp=sharing |
| アリの生態研究（〜全滅まで〜） | 理科（生物基礎） | https://drive.google.com/file/d/1_dJTOqolQD_z8JsqwgNEeO_6er5ulsx_/view?usp=sharing |
| 私の人生メモリー | 外国語科（論理表現Ⅰ） | https://drive.google.com/file/d/1V0LBC7XvN9tR_qgdgC6u5SK_Hry8i_Bl/view?usp=sharing |
| 変化球の投げ方について | 保健体育科（体育） | https://drive.google.com/file/d/1m9nKfK6eYLy1tu-vhia5GmkEZBDujh4d/view?usp=sharing |
| 空き瓶とガラスペイントでインテリア制作 | 芸術科（美術Ⅰ） | https://drive.google.com/file/d/1TDQ__bpVoJME5Q72bl990hzSaTinij1n/view?usp=sharing |
| アメ | 家庭科（家庭総合） | https://drive.google.com/file/d/13Cx5fadhWF3DtjCN44hAeSLHsu2RXJx1/view?usp=sharing |
| 自作PCでAIと向き合ってみた | 情報科（情報Ⅰ） | https://drive.google.com/file/d/1VX16bo4O3StKVvPd3o7C3o9MPT5623g9/view?usp=sharing |

---

## 現状のLP構成

```
award_winners.html
├── <header class="hero">        ← タイトル・ロゴ・キャッチ
├── <nav class="filter-nav">     ← カテゴリフィルター（sticky）
└── <main>
    ├── section[課題解決型]      ← 3件
    ├── section[創造型]          ← 2件
    ├── section[知的発見型]      ← 3件
    └── section[教科推薦]        ← 10件
```

### カードの構造（1枚あたり）

```html
<div class="card [top-award|mid-award|special-award|subject-award]">
  <div class="card-inner">
    <div class="card-tags">
      <span class="tag tag-[賞種別]">🏆 最優秀賞</span>
      <span class="tag tag-category">課題解決型</span>
    </div>
    <p class="card-title">作品タイトル</p>
    <p class="card-desc">作品説明（3行クランプ）</p>
    <div class="card-judge">
      <p class="card-judge-label">審査員講評 — ○○先生</p>
      <p class="card-judge-text">講評テキスト（2行クランプ）</p>
    </div>
    <a class="card-link" href="[Google Drive URL]">作品を見る →</a>
  </div>
</div>
```

---

## 今後の作業候補（Claude Codeで継続推奨）

- [ ] Next.js / Astroへのコンポーネント化
- [ ] 作品データをJSON/CMSに分離（データとUIの分離）
- [ ] Google Driveリンクをプレビュー表示（iframe埋め込み or サムネイル取得）
- [ ] OGP・メタタグ設定
- [ ] 公開デプロイ（Vercel等）
- [ ] 印刷用CSSの追加

---

## リンク元情報

- 元のQRコードSVG格納フォルダ：  
  https://drive.google.com/drive/folders/1yIaYiSr3LlqGBfjjbLdYB9poZmXiLxBN

- 元のPDFファイル：  
  `2025_マイプロアワード受賞作品紹介.pdf`（同梱）

---

*このドキュメントはClaude.ai（claude-sonnet-4-6）にて自動生成。2026-04-20*
