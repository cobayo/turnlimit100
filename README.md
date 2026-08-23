# TURN LIMIT 100 — Landing Page

`TURN LIMIT 100`（Steam App ID: 5116540）の公式ランディングページ。GitHub Pagesでホスティングする。

- 本体：`index.html`（単一ファイル・ビルド不要・外部依存なし。フォント/画像は全てdata URIで埋め込み済み）
- ソース元：`kobayo/kutasta_game` リポジトリの `steam-assets/` 配下の素材、および
  `docs/steam-release-checklist.md` §10 のストア説明文コピーをベースに構成
- 更新するときは `index.html` を直接編集してcommit/pushするだけでよい（GitHub Pagesが自動再配信する）

## GitHub Pagesの設定（初回のみ・手動）

このリポジトリの Settings → Pages → Build and deployment → Source を
**"Deploy from a branch"**、Branch を **`main` / `/(root)`** に設定して Save。
数分で `https://cobayo.github.io/turnlimit100/` が有効になる。
