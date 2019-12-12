# Hugo多言語テンプレート

## :question: これは何ですか？
[Hugo](https://gohugo.io/)は静的サイトジェネレーターと呼ばれる種類のオープンソースプロジェクトです。テンプレートから完成されたHTMLを生成するため、スクリプトによる動的生成に比べて、サーバーでの負荷が少なくなるメリットがあります。

このプロジェクトは、Hugoにおいて多言語環境(i18n)を簡単に構築するためのサンプルです。

Hugoではフォルダーを用意するだけでも多言語化は可能ですが、従来の手法では、わずかでもレイアウトを変更しなければならないと、言語ごとにすべてのmdファイルを修正しなければいけません。

このテンプレートでは、ショートコードを活用することで、言語リソース単位での作成を可能にしています。

![Template image](conv.png)

toml(json/yaml)にページごとのテキストを記述しておけば、mdファイルを修正する必要が生じても、最小限の手間で済むようになるでしょう。

## :yen: 寄付歓迎！
[![Donate For Free Project](https://www.tnksoft.com/donate/donate.svg "Donate For Free Project")](https://www.tnksoft.com/donate/?lang=en)

## :copyright: License
[MIT](http://opensource.org/licenses/MIT)