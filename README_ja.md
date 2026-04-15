# Bay Area Tech Map

サンフランシスコ・ベイエリアの200社以上のテック企業を表示するインタラクティブマップです。Leaflet.jsとStamen水彩タイルを使用して構築されています。

**[ライブマップを見る](https://your-username.github.io/bay-area-tech-map/)** <!-- GitHub Pagesデプロイ後に実際のURLに置き換えてください -->

![Bay Area Tech Map スクリーンショット](screenshot.png)

> *他の言語: [English](README.md) | [中文](README_zh.md)*

## 特徴

- **208社の検証済み企業** — YCスタートアップからFAANGまで、すべて実際のオフィス住所
- **水彩画スタイルの地図** — Stamenタイルによる手描き風の美しいデザイン
- **企業ロゴ** — 有名企業はロゴがマップマーカーとして表示
- **検索とフィルター** — 名前、説明、カテゴリーで企業を検索
- **16カテゴリー** — AI、フィンテック、SaaS、コンシューマー、DevTools、ハードウェアなど
- **マーカークラスタリング** — SoMAのような密集エリアでもクリーンな表示

## クイックスタート

```bash
# リポジトリをクローン
git clone https://github.com/your-username/bay-area-tech-map.git
cd bay-area-tech-map

# ローカルで起動（任意の静的サーバー）
npx serve .
# または
python3 -m http.server 3000
```

[http://localhost:3000](http://localhost:3000) を開いてください。

## コントリビュート

企業を追加したいですか？詳しくは [CONTRIBUTING.md](CONTRIBUTING.md) をご覧ください。

**2つの方法：**
1. `companies.json` を編集してPRを提出
2. [Issueを作成](../../issues/new?template=add-company.yml) して企業情報を記入

すべての住所は検証されます。バーチャルオフィスや登録代理人の住所は受け付けません。

## ライセンス

[MIT](LICENSE)
