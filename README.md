# corebridges-site

コアブリッジの公式サイト。**となりAI（塾）** と **となりAIクエスト（コミュニティ）** の2本立て。

## ページ構成
| ファイル | 内容 |
|---|---|
| `index.html` | となりAI（塾）— マンツーマン／少人数の本格AI講座のランディング |
| `quest.html` | となりAIクエスト — ゲーム/RPG風のAIコミュニティ。加入フォーム・解約導線つき |
| `legal.html` | 特定商取引法に基づく表記／キャンセル・返金／プライバシー／利用規約（**下書き**） |
| `sitemap.xml` / `robots.txt` | SEO用 |
| `image/` | サイト画像（`image/quest/` は提案資料スライド） |

## 公開中の関連
- 本番ドメイン: https://corebridges.site
- 決済（かんたん契約）: https://nimble-bonbon-16d2b8.netlify.app
- LINE: https://lin.ee/RNf6mxZ

## TODO（公開前に必要な作業）
- [ ] **Stripe**: 支払いリンク（月¥1,000 / 月¥3,000 のサブスク、各単発）とカスタマーポータルURLを発行し、`quest.html` 冒頭の `LINKS` 設定に貼る
- [ ] **法務**: `legal.html` の「要記入」箇所（正式な事業者名・連絡用メール・税込/税抜・返金条件・制定日・管轄）を埋め、専門家のリーガルチェックを受ける
- [ ] **料金の最終確定**: 塾（A〜F）とクエスト資料の価格の食い違いを統一

## 開発メモ
静的サイト（ビルド不要）。ローカル確認は以下:

```bash
python -m http.server 8000
# → http://localhost:8000/
```
