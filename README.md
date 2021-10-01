# PHPでデザインパターンを学ぶリポジトリ

## 概要

[PHPによるデザインパターン入門](https://shimooka.hateblo.jp/entry/20141211/1418298136) を元にデザインパターンを勉強するリポジトリ

## インストール

```shell
git clone git@github.com:Y-Fujikawa/study-design-patterns-for-php.git
rm -fr ./src/*
docker-compose build
docker-compose up
```

## やり方

概要にあるページを確認して、デザインパターンごとにディレクトリを作成して写経する。

例： `TemplateMethod` の場合

```shell
mkdir TemplateMethod
cd TemplateMethod
```

各デザインパターンごとのディレクトリ配下で写経する。

`http://localhost/` にアクセスして各デザインパターンの結果を確認する。
