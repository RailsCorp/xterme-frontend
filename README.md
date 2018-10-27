# xtreme-frontend

> 使用フレームワーク : Nuxt.js
> xtremeのフロントエンド用アプリケーション
> パッケージ管理マネージャ : yarn

## 環境構築

macであることを推奨！

``` bash

yarnをインストールしていない場合！
$ brew install yarn
※ npm からのインストールはオススメされていない。

※ vue/cliが入っていな場合
$ yarn global add @vue/cli

 yarn がインストールされたか確認
 $ yarn --version

# install dependencies
$ yarn install

# localhost:3000にアクセス
$ yarn run dev   # rails sと同じ

# build for production and launch server
$ yarn run build
$ yarn start

# generate static project
$ yarn run generate
```

## テスト
```
	ava , jsdom
```
https://ja.nuxtjs.org/guide/development-tools/

を参照！

### ESlintとPrettier

ESlint : コードを綺麗に保つ優れたツール
Prettier : とても人気のあるコードフォーマッタ
