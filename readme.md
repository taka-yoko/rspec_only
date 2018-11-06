# Rails上ではないRspecテスト実行環境

## 参考
http://rspec.info/
https://qiita.com/yusabana/items/db44b81bdddf6ed0e9f5

## 設定

### Gemfile作成
```
$ bundle init
```

### Gemfileに追加
```
gem 'rspec', '~> 3.0'
```

```
$ bundle install
```
`vendor/bundle`配下にRspec関連ファイルがインストールされる。

## ディレクトリ構成
```
.
├── Gemfile
├── Gemfile.lock
├── lib
│   └── hello.rb
├── readme.md
├── spec
│   ├── examples.txt
│   ├── hello_spec.rb
│   └── spec_helper.rb
└── vendor
```
`lib`以下にテストしたいファイルを配置。
`spec`以下にspecファイルを配置。

テスト実行
```
bundle exec rspec
```
