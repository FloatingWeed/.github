# GitHub Template

[GitHubテンプレート用](https://help.github.com/en/articles/manually-creating-a-single-issue-template-for-your-repository)のリポジトリです。

[確認はこちらから](https://github.com/yousan/github_template/issues/new/choose)

# 内容
二種類のIssueテンプレートが入っています。

簡易版は普段書くためのテンプレートです。
<img width="641" alt="Screen Shot 2019-04-08 at 17 23 10" src="https://user-images.githubusercontent.com/561613/55709313-0671fe80-5a23-11e9-8230-c2cecc1d6e22.png">

詳細版はIssueを書くことに慣れていない人向けのテンプレートです。
<img width="789" alt="Screen Shot 2019-04-08 at 17 22 58" src="https://user-images.githubusercontent.com/561613/55709315-0671fe80-5a23-11e9-8f8b-652ed116bb3c.png">
<img width="630" alt="Screen Shot 2019-04-08 at 17 23 03" src="https://user-images.githubusercontent.com/561613/55709314-0671fe80-5a23-11e9-957e-89467a41e7cc.png">

テンプレートを導入しても、テンプレート無しでももちろん書けます。
<img width="361" alt="Screen Shot 2019-04-08 at 17 23 16" src="https://user-images.githubusercontent.com/561613/55709310-0671fe80-5a23-11e9-91a4-7e0476d37e3e.png">

デフォルトのラベルをつけることもできます。

<img width="288" alt="Screen Shot 2019-04-08 at 17 25 01" src="https://user-images.githubusercontent.com/561613/55709783-08888d00-5a24-11e9-8986-dc56a5b41b21.png">

ちなみに仕様かバグかの境界線上の場合、`bug`のラベルより`enhancement`のラベルの方がエンジニア受けが良いです 👼

# インストール方法
リポジトリ直下から`.github/ISSUE_TEMPLATE`ディレクトリにテンプレートファイルをダウンロードします。

下記のようにするとディレクトリを作成してファイルをダウンロード、保存します。

```bash
$ curl https://raw.githubusercontent.com/yousan/github_template/master/install.sh | sh - 
```

下記のコマンドでダウンロードできます。

```bash
$ mkdir -p .github/ISSUE_TEMPLATE

$ curl -o .github/ISSUE_TEMPLATE/default.md https://raw.githubusercontent.com/yousan/github_template/master/.github/ISSUE_TEMPLATE/default.md
$ curl -o .github/ISSUE_TEMPLATE/detailed.md https://raw.githubusercontent.com/yousan/github_template/master/.github/ISSUE_TEMPLATE/detailed.md
```

# テンプレート自体について
テンプレートの内容は自分が書いたほうが良いことを記述しています。
閉じられなくなってしまったタスクや、どうしたら良いのか迷わないように項目を立てています。


# 参考
https://tech.gamewith.co.jp/entry/2018/05/22/154951

https://engineering.crocos.jp/post/98455177675/pull-request-%E3%81%AE%E3%83%95%E3%82%A9%E3%83%BC%E3%83%9E%E3%83%83%E3%83%88%E3%82%92%E6%B1%BA%E3%82%81%E3%82%8B%E3%81%A8%E3%83%AC%E3%83%93%E3%83%A5%E3%83%BC%E3%81%AE%E5%8A%B9%E7%8E%87%E3%81%8C3%E5%80%8D%E3%82%88%E3%81%8F%E3%81%AA%E3%82%8B
