# bookpocket-site

Book Pocket（Web / PWA の本棚アプリ）の公開先です。アプリ本体の非公開リポジトリとは別に、生成済みの公開資材を配置します。

- [本棚](https://kyzw.github.io/bookpocket-site/)
- [プライバシーポリシー](https://kyzw.github.io/bookpocket-site/privacy-policy/)
- [お問い合わせ（GitHub Issues）](https://github.com/kyzw/bookpocket-site/issues)

上記は公開予定のURLです。Pages設定と配信完了後に疎通を確認してください。

## GitHub Pages への公開

現在のWeb公開経路は、アプリ本体リポジトリの手動デプロイworkflowでビルドした成果物を、このリポジトリの **`gh-pages`** ブランチへ配置する方式です。Pagesの公開元は **Deploy from a branch → gh-pages / (root)** に設定します。Web移行前の「main / (root)」の手順は使用しません。

本番公開の設定・デプロイは所有者がレビュー後に実施します。このPRのマージだけでは、公開済みとは扱いません。

## ポリシー本文の更新

`privacy-policy/index.html` は、本文のレビューと単体確認用のコピーです。原本はアプリ本体リポジトリの `docs/privacy-policy/index.html`。Webのビルド時に公開資材へコピーされ、`dist/privacy-policy/index.html` としてWebと同時に配信されます。本文の改訂は原本で行い、適用日も揃えてください。

本番の `gh-pages` はビルド成果物で置き換わるため、手動で編集しません。アプリ本体の内部資料や接続情報をこの公開リポジトリへコピーしないでください。ポリシーのHTML単体は外部スクリプト・画像・フォントを使いません。

公開後に、ログインしていないPC・実iPhoneで本文と問い合わせ先を開けること、PWAのアプリ画面からリンクで到達できることを確認します。

問い合わせ窓口は公開Issuesです。投稿にはGitHubアカウントが必要で、内容は公開されます。個人情報・認証情報や本棚のスクリーンショットを投稿しない案内を維持してください。
