---
title: リポジトリの言語について
intro: リポジトリ内のファイルやディレクトリが、リポジトリを構成する言語を決定します。 リポジトリの言語を見れば、そのリポジトリの簡単な概要が得られます。
redirect_from:
  - /articles/my-repository-is-marked-as-the-wrong-language/
  - /articles/why-isn-t-my-favorite-language-recognized/
  - /articles/my-repo-is-marked-as-the-wrong-language/
  - /articles/why-isn-t-sql-recognized-as-a-language/
  - /articles/why-isn-t-my-favorite-language-recognized-by-github/
  - /articles/about-repository-languages
versions:
  free-pro-team: '*'
  enterprise-server: '*'
---

構文強調やリポジトリ統計のためには言語を特定する必要があります。{% data variables.product.product_name %}ではオープンソースの [Linguist ライブラリ](https://github.com/github/linguist)を使用して言語を特定します。 Language statistics will update after you push changes to your default branch.

ファイルによっては特定しにくいものもあります。また、プロジェクトによっては、主たるコード以外のライブラリやベンダーファイルが含まれていることもあります。 誤った結果が返される場合は、Linguist の [トラブルシューティングガイド](https://github.com/github/linguist#troubleshooting)を調べてみてください。

### マークアップ言語

マークアップ言語は HTML にレンダリングされ、弊社のオープンソース[マークアップライブラリ](https://github.com/github/markup)を使ってインラインで表示されます。 現時点では、{% data variables.product.product_name %}内で表示する新しいマークアップ言語は受け付けていません。 しかし、弊社は現在のマークアップ言語群を積極的にメンテナンスしています。 もしも問題があれば、[Issue を作成してください](https://github.com/github/markup/issues/new)。
