# 全ロボ参加者のためのチュートリアル

[![GitHub License](https://img.shields.io/github/license/aKuad/zenrobo-tutorial?logo=creative-commons)](https://github.com/aKuad/zenrobo-tutorial/blob/main/LICENSE)

> このサイトでは、全ロボ参加にあたって知っておくとよさそうなことを紹介します。

全ロボこと全国ロボコン交流会の参加経験者から、参加におけるヒントを共有したいと思い、サイトを立ち上げました。

docsify を用いて、markdown で記述された文書を静的 Web ページとして配信しています。サーバは GitHub Pages を利用しています。

<https://akuad.github.io/zenrobo-tutorial>

編集ガイドラインは [CONTRIBUTING.md](./CONTRIBUTING.md) を参照してください。

## プレビュー方法

npm から docsify をインストールし、`docs` をルートにサーバを起動します。

```sh
npm install -g docsify-cli  # インストールは初回のみ
docsify serve docs

# または

npx docsify-cli serve docs
```

あとは `http://localhost:3000/` にアクセスすれば、ページを閲覧できます。

## ライセンス

気軽に使ってもらうために、本サイトのコンテンツは CC0 ライセンスで公開しています。

断りなく、自由に改変や再配布が可能です。著者の表記も必要ありません。
