# 職務経歴書

リポジトリ: [https://github.com/monkeyWzr/resume](https://github.com/monkeyWzr/resume)

## 基本情報

|キー|バリュー|
|----|-------|
|姓名|呉澤冉(ゴ タクゼン)/WU ZERAN|
|生年月|平成8年6月/1996.6|
|GitHub|[monkeyWzr](https://github.com/monkeyWzr)|
|Twitter|[@monkeywzr](https://twitter.com/monkeywzr)|
|LinkedIn|[呉 澤冉 (WU ZERAN)](https://www.linkedin.com/in/monkeywzr/)|
|Blog|[https://www.takuzen.me/](https://www.takuzen.me/)|

## 概要

2018年8月下旬中国から日本に来て新卒エンジニアとして会社に入りました。

今までやってきた仕事は：Spring+Vue.js+TypeScriptベースの社内フレームワークで新規機能の開発、Strutsベースの社内独自フレームワークのWEBアプリケーションの保守、PL/SQLとJP1でバッチ保守と開発、およそ2年半ぐらいの開発実務経験があります。日本語もプログラミングもマナーも勉強しながら応用することが多くて、とても充実した楽しい日々を体験しています。

将来はWEBアプリケーションエンジニアとしてモダンな開発スタイルを中心に、技術を活用することで、大規模なサービスから生み出した課題を挑戦できる仕事をやりたいと思います！ Web開発の技術スタックをより深く経験したくて、Ruby、Node.js、AWS、DevOpsなどの技術も実践してみたいと思います。

プログラミング言語技術、ソフトウェア開発方法論などに興味があります。技術以外はドラム、ウクレレ、スキーが好きです。

## スキル

### 自然言語

* 日本語:
  - N1: 144点/180点(2020年12月)
  - 敬語が大好きなので、正しく使えるように命をかけて頑張っています(上司に「ご苦労様」を使うこととか2度としたくないです！)
* 英語:
  - TOEIC: 935点(2021年2月)；835点(2017年)
  - ドキュメント、技術本などを読むこと、READMEなどを書くことができます
  - 簡単な日常会話ができます
* 中国語
  - ネイティブ

### プログラミング言語

* Java
* JavaScript
* TypeScript
* PL/SQL

### フレームワーク

* Spring/Spring Boot
* Vue.js

### ツール

* Git 日常に使っています

### 資格

* 応用情報技術者(2019年10月)
* RPA Developer Advanced(2019年12月)

### その他

Couseraで複数のオンラインコースを修了したことがあります。認定番号は[LinkedIn](https://www.linkedin.com/in/monkeywzr/)で記載しております。

* **Programming Language Part A, B, C** SML、Racket、Rubyを使った、凄く面白いコースだと思います

最近はSwift/iOS開発を勉強しています。

### OSSプロジェクト

* hugoテーマ [hugo-theme-cactus](https://github.com/monkeyWzr/hugo-theme-cactus)
  - 静的サイトジェネレータの一つであるHugoのテーマ
  - もともと使ったhexoテーマcactusが大好きなので、hugoにポートしました

* 個人ブログ [https://github.com/monkeyWzr/monkeywzr.github.io](https://github.com/monkeyWzr/monkeywzr.github.io)
  - Hugo + GitHub Pages + Travis CI
  - srcブランチでブログのソースを管理して、TravisCI自動デプロイする

## 職務経歴

2018年8月新卒入社から2年半ぐらいの開発実務経験があります。

### 2018/8 - 2021/6 : ベース株式会社

職務: WEBアプリケーションエンジニア(客先常駐)

#### 新規WEBサービスの開発(2020.7 - 2020.12)

店頭、対面等オフライン方式で入会した会員のオンライン登録、及びログインID、パスワードの変更機能を提供するWEBアプリケーション

* Spring BootによるRESTful API + TypeScript + Vue.jsによるSPA + Orcaleデータベース
* 電話発信サービスTwilioの導入と誤送信防止対策、SPAサイトにおけるアナリティクスサービス(gtag、karte)の設置
* 詳細設計と実装を担当しました。下記の課題を解決しました
  - SpringのArgumentResolver、RequestBodyAdviceを使ってサーバ側のAPI項目共通バリデーション
  - Vue.jsのVuelidateのバリデーターを実装して入力フォームのカスタマイズバリデーション
  - TypeScriptの活用でソース闇に隠れているバグがコンパイル時に発見
  - etc.

#### PL/SQLバッチの保守と開発(2019.4 - 2020.6)

消費税増税に伴うデータ作成バッチの修正、新規値引き企画のデータ作成バッチグループの実装なとを担当しました

* PL/SQLによるプロシージャの新規/改修
* JP1によるジョブの運用管理

#### Vue.jsによる既存サイトのレスポンシブ共通化(2018.12 - 2019.4)

既存PCサイト、SPサイト、ネイティブアプリの共通化対応。1つの画面のVue実装と複数画面のバグ修正を担当しました。

* Vue.jsを初めて実務に使いました
* JavaScriptをよりよく理解し、Promiseのコールバックチーンの概念を習得しました

#### 複数既存WEBサービスの保守(2018.10 - 2019.4)

* Strutsベース、S2Clickベースの社内独自フレームワーク
* 画面テンプレート修正、Javaロジック修正とか簡単な作業を担当しました
* 人生初めての実務作業であり、Eclipse + Tomcatでプロジェクトのローカル環境構築が難しかった


## 自己PR

私は技術に強い好奇心を持っています。新しいことを学ぶこと、納得まで深く探索することが大好きです。

例えば、下記のようなJavaコードを書いてしまって、

`Arrays.asList(new int[]{1, 2, 3}).forEach(i -> System.out.println(i + " "));`

謎と思った出力になりましたので、調査しました。JavaのVarargs、ジェネリクスから始め、バイトコードにも初めて突っ込んで、Varargsの本質、Autoboxingの発生タイミングなどを検証してみました。

Springを使って開発していた時、「いつもgetters/settersを定義する理由は何でしたっけ？」と理解できず、調査してみました。結果、JavaBeanの誕生からServlet、EJB、ORM等々Javaエコシステムの歴史と発展をなぞって、ついにPOJO、DTO、Beanなどわかったようなわからないような概念をクリアしました。

大学時代からGitHub Pagesで静的ブログを運用して個人ブログを書き続け、主に学習メモを内容として書きました。ジェネレータツールをHexoからHugoに移行した時、大好きのテーマもHugoに移行し、OSSプロジェクトとして公開しました。スター、Issues、PRをたくさんもらって、とても楽しかったです。

今後の目標は知識レベルアップ、ボトルネックの突破です。具体的にいうと、より良い質なコードを書けることを目指して、デザインパターン、OOPなどソフトウェア開発方法論を勉強したいと思います。そして、業務中のソースを読んだり、OSSプロジェクトのソースを読んだり、どの手法が応用されるのか、どのようなリファクタリングが必要か、などのことを考えながら実践できればと思います。Java、TypeScriptなど自分が最近慣れている言語を出発点として、型システム、コンパイラ、仮想マシンなどの言語技術も勉強したいと思います。

私は技術に熱情を持っている仲間と一緒に働き、技術力が高いハックな環境で成長し、会社に、技術コミュニティに自分の熱情を貢献したいと思います。面白いプロジェクトを作ったり、技術勉強会を参加しったり、OSSプロジェクトに参加したり、色々なエンジニアと出会って、技術の楽しみをたっぷりと味わいたいと思います。

## この先やってみたいこと

### 業務内

* Spring、Node.js + TypeScriptなどをベースしたサーバーサイト開発
* Ruby/RailsをベースしたWEBサービスの開発
* AWSなどを活用した開発
* DevOpsツールを導入したモダンな開発

### 業務外

* ネットワーク技術の勉強
* Swiftを使ったiOSアプリの開発
* Rustなど新言語を利用したソフトウェア開発
* AtCoder/LeetCodeでアルゴリズムの練習
* 型システム、型理論、コンパイラ、VMなどプログラミング言語技術の勉強
