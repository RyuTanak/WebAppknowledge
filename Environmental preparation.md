# 環境準備  

Node.jsをPCに直接インストールしない理由  
```
1つのPCでバージョンが違うNode.jsを使うときがあるから
```

そのため、今回はasdfという、複数バージョンのNode.jsをインストールできるツールを使用します。  

<br>

## asdfのインストール手順  

公式ドキュメントは[こちら](https://asdf-vm.com/guide/getting-started.html)  

公式ドキュメントの説明にはLinuxOSとMacOSのインストール手順が記載されているが  
Windowsでのインストール手順がないため、WSL2を使用します。  

Powershellで以下のコマンドを実行  
```
wsl install
```

## asdfでnode.jsを用意する  

powershellでwslに入る  
```
.\wsl
```
