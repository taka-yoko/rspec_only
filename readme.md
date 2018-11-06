# Rails上ではないRspecテスト実行環境


## 参考
http://rspec.info/
https://qiita.com/yusabana/items/db44b81bdddf6ed0e9f5


```
$ bundle init
```

Gemfileに追加
```
gem 'rspec', '~> 3.0'
```

```
$ bundle install
```
`vendor/bundle`配下にRspec関連ファイルがインストールされる。


ディレクトリ構成
```

```

テスト実行
```
bundle exec rspec
```
