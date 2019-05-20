# remark-preset-lint
akashic-gamesリポジトリで共通的に利用するremarkプリセットです。

## 使い方
### インストール
```sh
npm install --save-dev remark-cli @akashic/remark-preset-lint
```

### 設定ファイルの書き方
`.remarkrc` に以下のように記載します。
```json
{
  "plugins": [
    "@akashic/remark-preset-lint"
  ]
}
```

### 実行方法
```sh
remark . --frail --no-stdout --quiet --rc-path ./.remarkrc
```

## ライセンス
本リポジトリは MIT License の元で公開されています。
詳しくは [LICENSE](https://github.com/akashic-games/remark-preset-lint/blob/master/LICENSE) をご覧ください。

ただし、画像ファイルおよび音声ファイルは
[CC BY 2.1 JP](https://creativecommons.org/licenses/by/2.1/jp/) の元で公開されています。
