# 小瑠璃フォント (Koruri)

すっきりと可読性を高めたオープンソースの日本語フォント

## 概要

『小瑠璃フォント (Koruri)』は、M+ 1p をベースに英数字グリフを Open Sans に差し替えたフォントで、英数字を多く含む文章の可読性が本家 M+ 1p に比べて高まることが期待されます(効果には個人差が有ります)。

M+ FONTS と Open Sans の制作に関わる全ての方に深くお礼申し上げます。

## インストール方法

### Windows の場合

この README を読めているということは、アーカイブの解凍までは成功していると思われますので、Windows Vista 以降で管理者権限を持つアカウントの場合は .ttf ファイルを開いてインストールできるはずです。 

### OS X の場合

この README を読めているということは、アーカイブの解凍までは成功していると思われますので、.ttf ファイルを /Library/Fonts ディレクトリにコピーするとインストールできるはずです。

### Linux の場合

この README を読めているということは、アーカイブの解凍までは成功していると思われますので、お使いのシステムに gnome-font-viewer がインストールされている場合は、 .ttf ファイルを開いてインストールできるはずです。

それ以外の場合でも、 ~/.fonts に .ttf ファイルをコピーして % fc-cache -fv でフォントのキャッシュを更新するとインストールされます。

## 解説

### フォントの構成

小瑠璃フォント (koruri) は、 M+ 1p をベースに Open Sans と同じ5つのウエイトから構成されています。
組み合わせは以下のとおりです。

- Regular: **M+ 1p Regular** と **Open Sans Regular** の合成
- Light: **M+ 1p Light** と **Open Sans Light** の合成
- Semibold: **M+ 1p Medium** と **Open Sans Semibold** の合成
- Bold: **M+ 1p Bold** と **Open Sans Bold** の合成
- Extrabold: **M+ 1p Black** と **Open Sans Extrabold** の合成

Koruri-20140524 では、 M+ TESTFLIGHT 058 (2014.02.26) と Open Sans 1.10 を使用しています。

### 制作方法

Koruri-20140510から、 @mandel59 さんによる生成スクリプトで生成しています。
Koruri-20140524では [https://gist.github.com/lindwurm/b24657c335bb11a520c4/9461c1690188ddd2b6d721467653e6e0072689b8] を使用しました。

## ライセンスについて

ライセンスは、Open Sans 側の Apache License 2.0 に準じます。

同梱の LICENSE.txt をご覧ください。

## リンク

- M+ FONTS [http://mplus-fonts.sourceforge.jp]
- Open Sans [http://www.opensans.com]
- FontForge [http://www.fontforge.org/ja/]

## 連絡先

一番早いのは Twitter だと思います。メールは日に一度見るか見ないか程度です。

### lindwurm (Hotaka Hitagi)

- Website [http://lindwurm.biz]
- Twitter [https://twitter.com/lindwurm]

### Koruri

- Portal/Website [http://koruri.lindwurm.biz]
- GitHub [https://github.com/Koruri/Koruri]
- Project in SourceForge.JP [https://sourceforge.jp/projects/koruri/]

## 更新履歴

SourceForge.JP のプロジェクトページをご確認ください。
