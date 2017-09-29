# practice  
### 具体的に準備を始める前に、「pythonって何？」という方は、[こちら](https://www.python.jp/about/)を一読ください。    
### すでに自身のPCにpythonの環境が整っている方は、pipやwheel、homebrewなどが使える状態だと思います。本演習ではnumpy, matplotlib, pandas, basemapを使いますので、自分の知っている方法でこれらのパッケージをインストールしてください。以下の手順は不要です。  
## 1. python環境構築
Anacondaをインストールします。  
Anacondaは、pythonに加えて、データ解析によく使われるpythonパッケージや、パッケージ管理システム(conda)を内包しています。なので、Anacondaをインストールするだけで、ある程度pythonの環境が整います。  
以下のサイトから、**"python3.6 version"** かつ自分のOSに合うインストーラーをダウンロードし、インストールしてください。  
<https://www.anaconda.com/download/>  
上記のサイトにドキュメンテーションもあるので、わからなければ参考にしてください。  
## 2. Basemapのインストール
Anacondaのインストールに成功したら、次にBasemapをインストールします。  
Basemapは、pythonで地図描画をするのに便利なパッケージです。  
以下の手順に従ってください。
### step1
windowsは、コマンドプロンプト  
macは、ターミナル  
をそれぞれ起動してください。
### step2
コマンドプロンプト、ターミナル、いづれもAnacondaがインストールされていれば”conda”というコマンドを使えるようになります。  
`conda install basemap`
