# Laptop

## 環境

* Mac OS X 10.8 (Mountain Lion)


## 手順

### Command Line Tools for Xcodeをインストールする

Xcodeからインストールすることができます。


### Laptopのプログラムを実行する

```
bash <(curl -s https://raw.github.com/bojovs/laptop/master/mac)
```

## 行なっていること

* SSH鍵の作成
* Homebrewのインストール
* Rubyのインストールに必要なパッケージのインストール
  * autoconf
  * automake
  * apple-gcc42
  * gdbm
  * libffi
  * libksba
  * libyaml
* MySQLのインストール
* Redisのインストール
* ImageMagickのインストール
* Qtのインストール
* RVMのインストール
  * Ruby 1.9.2-p318のインストール
  * Ruby 1.9.3-p125のインストール


## その他

### 初期化の手順

```
$ rm -rf ~/.ssh
$ rvm implode
$ rm -rf /usr/local/Cellar /usr/local/.git && brew cleanup
```

https://gist.github.com/mxcl/1173223


## License

Laptop is © 2011-2013 thoughtbot, inc. It is free software, and may be
redistributed under the terms specified in the LICENSE file.
