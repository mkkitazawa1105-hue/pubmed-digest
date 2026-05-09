# PubMed論文ダイジェスト

北澤勝（新潟大学・糖尿病/内分泌研究）の関心領域に絞ったPubMed論文ダイジェストの自動公開リポジトリです。

## 関心トピック
- 糖尿病発症予防（incidence prevention）
- 1型糖尿病治療
- 先進医療機器・デジタルヘルス（CGM、AID、SyncHealth等）
- その他（領域横断・総説等）

## ファイル構成
- `latest.html` — 最新ダイジェスト（自動上書き）
- `YYYYMMDD.html` — 日付別アーカイブ（直近7日分のみ保持）
- `index.html` — `latest.html` へリダイレクト

## 公開設定
- 検索エンジン除外（noindex/nofollow）
- 個人情報・要配慮情報は一切含まれない
- 内容は公開論文情報のみ

## 自動化
Mac mini（Claude Code Desktop）の `pubmed-daily-digest` scheduled-task が月水金 21:00 に自動生成・自動コミット・自動Push します。
