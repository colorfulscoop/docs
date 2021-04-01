# Colorful Scoop ドキュメントサイト

## 参考情報

ドキュメントサイトのビルドには GitHub Pages のデフォルトの Jekyll を使う。
GitHub と Jekyll の関係については次を参照 https://docs.github.com/ja/github/working-with-github-pages/about-github-pages-and-jekyll

Note: なお、Jekyll 以外を使いたい場合はルートに `.nojekyll` というからのファイルを作成して、使っている静的サイトジェネレータで HTML をローカルビルドしてアップするということもできる。 https://docs.github.com/ja/github/working-with-github-pages/about-github-pages#static-site-generators

GitHub の Jekyll のデフォルトテーマには [primer](https://github.com/pages-themes/primer) が使われてる。
カスタム方法はこの Git リポジトリを参照するとよい。

Jekyll の設定に使う `_config.yml` はドキュメントルートにおく必要があるので、 `docs/` 以下を公開する場合には `docs/_config.yml` というファイルにする

ページレイアウトを変更するには、https://github.com/pages-themes/primer/ に従って `docs/_layouts/default.html` を配置して、その中にレイアウトをかく。
レイアウトの書き方は primer に付属している https://github.com/pages-themes/primer/blob/master/_layouts/default.html が参考になる。