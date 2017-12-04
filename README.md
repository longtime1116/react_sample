## 導入

### 1. 以下に従って作業

```bash
# package.json 作成
$ yarn init

# react/react-dom のインストールと、package.json への追加
# これにより node_modules ディレクトリと yarn.lock ファイルができる
$ yarn add react react-dom

# webpack と babel のインストール
$ yarn add --dev webpack babel-loader babel-core babel-preset-react babel-preset-es2015
```

### 2. webpack.config.js を作成

### 3. src 以下を作成

### 4. dest/index.html を作成

### 5. webpack で src 以下のファイルをバンドルする(良い感じに一つにまとめる)

以下を実行することで、dist/bundle.js が作成される

```bash
$ ./node_modules/.bin/webpack
```

エラーになる場合は、以下で詳細なメッセージを出力可能。
この時点でエラーになる場合はタイポを疑うべし

```bash
$ ./node_modules/.bin/webpack --display-error-details
```

ここまで行うと、index.html をブラウザで開いたときに Hello が表示されるようになっている



## TODO
* js 用の vim 設定 
