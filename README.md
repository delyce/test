# Vue Starter


## Description

Vue による Web アプリケーション開発のスターターキットです。


## Usage

### インストール

```
$ npm install
```

### デバッグサーバの起動

デバッグサーバを起動すると、
コンパイルされたプログラムがメモリ上にロードされます。

```
$ npm run serve
```

下記 URL から Web アプリケーションへアクセスできます。

http://localhost:8080/

### テスト JSON データの配置

**/test/{METHOD}.json** のように JSON データを配置すれば、
Web アプリケーションと JSON サーバとの簡易的な連携テストができます。
METHOD は、GET、POST、PUT、DELETE に対応してます。

### 本番用ビルド

Web サーバを介して、公開するためには本番用ビルドを実行します。
本番用ビルドを行うことで、Web アプリケーションに最適化できます。
ビルドしたファイルは、**/dist** に出力されます。

```
$ npm run clean
$ npm run build
```

### リポジトリのコピー

```
$ git clone --mirror https://github.com/delyce/vue-starter {NEW_NAME}
$ git remote set-url origin {NEW_REPOGITORY}
$ git push --mirror origin
```


## Licence

[MIT](https://www.opensource.org/licenses/mit-license.php)


## Authors

[delyce](https://github.com/delyce)
