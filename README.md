Locales for VanillaAddons
=========================

Vanilla アドオン用の日本語言語ファイルを管理します。

プラグインの言語ファイルには、以下の 2 形式の提供方法があります。

* `/plugins/{Plugin-folder}/locale/{LocaleName}.php`
* `/plugins/{Plugin-folder}/locale/{LocaleName}/definitions.php`

プラグイン側に既に locale ディレクトリが存在している場合は、その形式に従います。

それ以外は、

    /plugins/{Plugin-folder}/locale/{LocaleName}.php

形式になっています。

テーマの言語ファイルは以下の 1 形式になります。

    /themes/{Theme-folder}/locale/{LocaleName}.php

各言語ファイルの翻訳対象は、Garden フレームワークの翻訳機能を利用しているコードに限られます。
それ以外の箇所は対象外です（例. CLEditor のツールバー）。

収録アドオン
------------

以下のアドオンを日本語化しています。

* Plugins
  * [Mark All Viewed](http://vanillaforums.org/addon/allviewed-plugin) 1.1 -- Vanilla 2.0.17.9 contains
  * [About Me](http://vanillaforums.org/addon/579-about-me) 1.0
  * [<Embed> Vanilla](http://vanillaforums.org/addon/embedvanilla-plugin) 1.0.1 -- Vanilla 2.0.17.9 contains
  * [ReplyTo](http://vanillaforums.org/addon/replyto-plugin) 0.1.8
* Themes
  * EmbedFriendly 1.0 -- Vanilla 2.0.17.9 contains


使い方
------

各アドオンのディレクトリに、日本語言語ファイルを含む locale フォルダを
コピー (フォルダがすでにあれば上書き) してください。

未翻訳箇所を見つけたら
----------------------

課題 (issues) に報告してください。

ただし、アドオン側で翻訳コードが提供されていない場合は、翻訳できません。

翻訳目的でアドオンをハックすることは、原則として行っていません。

またアドオンの作者に対して翻訳コードを提供するよう働きかける代行も、
原則として行っていません。

