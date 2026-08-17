# ツボ変換辞書 サポートサイト

「ツボ変換辞書」の公開用サポートページです。HTMLとCSSだけで構成し、アプリの経穴データや個人情報は含みません。

## ページ

- `index.html`：アプリの案内
- `privacy.html`：プライバシーポリシー
- `support.html`：設定方法、よくある質問、お問い合わせ
- `styles.css`：共通スタイル

## ローカル確認

このフォルダで次を実行し、表示されたURLをブラウザで開きます。

```sh
python3 -m http.server 8080
```

想定する公開先：

`https://satoshihasegawa.github.io/tsubo-henkan-support/`

## お問い合わせ先の変更

`support.html` 内の `CONTACT_LINK` コメントの直後にあるリンクを変更します。現在は次のGitHub Issuesを案内します。

`https://github.com/satoshihasegawa/tsubo-henkan-support/issues/new`

## 公開について

このフォルダはまだGitリポジトリとして初期化・公開していません。公開時は内容を最終確認してから、別途GitHub Pagesを設定してください。
