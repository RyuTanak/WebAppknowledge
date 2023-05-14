# npmでWebサーバのパッケージのインストール  

有名どころだと、「nginx」や「Apache HTTP Server」などがあります。  
今回は「http-server」というWebサーバを使用  

### npmとは  

Node Package Managerといい、Node.jsのパッケージを管理するツールのこと  
使用する言語によって色々ある。  

|Node.js|Ruby|Python|
|-|-|-|
|npm|Bundler|pip|
|package.json|Gemfile|requierments.txt|

以下のコマンドでnpmの準備  
```
npm init
```
カレントディレクトリに「package.json」が作成される  

以下のコマンドでhttp-serverをインストール  
```
npm install http-server
```

サーバの実行コマンドは  
```
npx http-server
```
