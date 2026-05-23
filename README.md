# yuudai-web3

CG / YouTube web app.  
「yuudai-web3」は、YouTube や動画視聴をより快適にするための Web アプリです。  
ブラウザからすぐにアクセスでき、PC・スマホ問わず軽量に動作することを目指しています。

### デモ
- https://yuudai-web3.vercel.app

---

## 特徴

- **軽量:** HTML + JavaScript ベースのシンプル構成
- **ホスティングしやすい:** Vercel / Render / Railway などの PaaS に対応しやすい構造
- **Node.js 対応:** `index.js` + `Procfile` によるサーバー起動が可能
- **設定ファイル付き:** `render.yaml` / `railway.json` などのデプロイ設定ファイルを同梱

---

## デプロイ

ワンクリックで自分の環境にデプロイできます。

### Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/kamikun0318/yuudai-web-3-1)

### Render

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?repo=https://github.com/kamikun0318/yuudai-web-3-1)

### Railway

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template?templateUrl=https://github.com/kamikun0318/yuudai-web-3-1)

---

## 必要要件

- **Node.js** (推奨: LTS)
- **npm** または **yarn**

---

## ローカル開発

```bash
# 依存関係のインストール
npm install

# 開発サーバー起動
npm start
# または
node index.js
```

---

## 更新履歴
### ver1.4.8
- yuudai-web3へのブランド統一
- Ballistic と EaglercraftJava ゲームを追加
- ロゴとテキストを完全に更新

### ver1.4.7
- webLLMを使用してAIをそのデバイスに建てて使えるように<br>
- ビデオ通話をできるように<br>
- Elixir-Networkを利用した漫画と映画鑑賞<br>
- gameの人気順の可視化

### ver1.4.2
- 人気ホラーゲーム「R.E.P.O」をはじめ、ブロスタ、ダダサバイバー、サンズ戦、ジオメトリーダッシュ、あつ森、クッキークリッカーなどの人気ゲームを追加
- クオリティが極限まで高いゲームをその他10個ほど追加
- 動作しなかったゲームの修正
- 動画サーバー Elixir をスマートフォンからでも使えるように強化
- 新しいプロキシ「GUST」を追加

### ver1.4.1
- Claude が無料で使えるように変更（認証が必要です）
- Portable 版のマインクラフトを追加
- ショート動画の埋め込み視聴に対応し、ショートの閲覧が可能に
- 新動画サーバー Elixir-Network を追加。Wisp サーバーの最適化により動画の読み込みを高速化

### ver1.4.0
- Elixir-Network と統合

### ver1.3.5
- Abyss V5 と統合
- アニメ視聴ページへのルートを修正

### ver1.3.0
**新機能**
- ホーム画面で「ホーム画面に追加」することで擬似アプリ化（Apple のみ）
- アニメ視聴ページを追加

---

## 技術詳細

### Elixir-Network について
高速で安定した動画ストリーミングプロキシ

### Abyss V5 について
UV ベースの静的プロキシ

このプロキシを単体で利用したい場合は、以下のリポジトリを推奨します。  
https://github.com/mino-hobby-pro/UV-Static_Netlify

---
## 開発メンバー

・<a href="https://github.com/kamikun0318">kamikun0318</a>  
・<a href="https://github.com/mino-hobby-pro">mino-hobby-pro</a>  
・<a href="https://github.com/myproxy0108-prog">myproxy0108-prog</a>  
・<a href="https://github.com/raku-ringo">raku-ringo</a>  
・<a href="https://github.com/Sou930">Sou930</a>  
・<a href="https://github.com/KA1121Studio">KA1121Studio</a>  
・<a href="https://github.com/woolisbest">woolisbest</a>  

---

<div align="center">

### yuudai-web3

© 2026 <a href="https://github.com/kamikun0318">kamikun0318</a>  
All rights reserved.

</div>
