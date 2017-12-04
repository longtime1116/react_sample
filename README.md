## 導入

## 1. 以下に従って作業

```bash
# package.json 作成
$ yarn init

# react/react-dom のインストールと、package.json への追加
# これにより node_modules ディレクトリと yarn.lock ファイルができる
$ yarn add react react-dom

# webpack と babel のインストール
$ yarn add --dev webpack babel-loader babel-core babel-preset-react babel-preset-es2015
```

## 2. webpack.config.js を作成

## 3. src 以下を作成

## 4. dest/index.html を作成

## 5. webpack で src ディレクトリのファイルをバンドルする

```bash
$ ./node_modules/.bin/webpack
```

エラーになる場合は、以下で詳細なメッセージを出力可能

```bash
$ ./node_modules/.bin/webpack --display-error-details
```

ここまで行うと、index.html をブラウザで開いたときに Hello が表示されるようになっている
