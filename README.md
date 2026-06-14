# driving-sim-legal

運転練習シミュレーターアプリの法的文書（利用規約・プライバシーポリシー・特定商取引法に基づく表記）を GitHub Pages（Jekyll + minima テーマ）で公開するためのリポジトリです。

## 公開URL（例）

- トップ: `https://berry8848.github.io/driving-sim-legal/`
- 利用規約: `https://berry8848.github.io/driving-sim-legal/terms/`
- プライバシーポリシー: `https://berry8848.github.io/driving-sim-legal/privacy/`
- 特定商取引法に基づく表記: `https://berry8848.github.io/driving-sim-legal/tokushoho/`

## 公開前チェックリスト

- [ ] 各ファイル内の `〔 〕` プレースホルダを実際の値に置換
  - `〔support@example.com〕` … 問い合わせメール
  - `〔事業者名（個人の場合は氏名）を記載〕` / `〔氏名を記載〕` … 特商法の事業者・責任者
- [ ] 所在地・電話番号を「請求時に開示」方式のままにするか、実値を常時掲載するか決定
- [ ] App Store Connect の「プライバシーポリシー URL」に privacy ページの URL を登録

## GitHub Pages の有効化手順

1. GitHub で公開リポジトリ `driving-sim-legal` を作成
2. このフォルダの中身を push（下記）
3. リポジトリの Settings → Pages → Build and deployment
   - Source: `Deploy from a branch`
   - Branch: `main` / `/ (root)` を選択して Save
4. 数分後、上記 URL で公開される

## ローカルプレビュー（任意）

```sh
gem install bundler jekyll
jekyll serve   # http://localhost:4000
```