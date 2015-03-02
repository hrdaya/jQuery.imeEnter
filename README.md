# jQuery.imeEnter
[![GitHub release](https://img.shields.io/badge/release-v0.1.1-blue.svg?style=flat)](https://github.com/hrdaya/jQuery.imeEnter/releases)
[![GitHub licence](https://img.shields.io/badge/licence-MIT-blue.svg?style=flat)](https://github.com/hrdaya/jQuery.imeEnter/blob/master/LICENSE)
[![devDependency Status](https://david-dm.org/hrdaya/jQuery.imeEnter/dev-status.svg)](https://david-dm.org/hrdaya/jQuery.imeEnter#info=devDependencies)

jQuery.imeEnterはIME入力確定・カット・ペースト時にイベントが発火されるプラグインです。
  IME入力中以外にはフィルタリング等を行いたくない場合に使用します。

 - バグや改善項目がありましたら[issue](https://github.com/hrdaya/jQuery.imeEnter/issues)を上げていただけると助かります :smiley:

## 使用方法

[ドキュメント](http://hrdaya.github.io/jQuery.imeEnter/)をご参照ください

## jQuery.imeEnterは次の時に「enter.imeEnter」というイベントが発火します

- IMEがoffの時に「keyup」した時
- IMEの入力が確定した時
- カットした時
- ペーストした時

## 適用されるエレメント

 - textarea
 - input（ただし下記の「type」は除く）

>  - password
>  - radio
>  - checkbox
>  - file
>  - hidden
>  - submit
>  - image
>  - reset
>  - button
>  - range

## 確認済みのブラウザ

「windows7 64bit」で下記のブラウザを使用して確認しています

 - Google Chrome
 - Firefox Developer Edition
 - Internet Explorer11

## ライセンス

[MIT License](https://github.com/hrdaya/jQuery.imeEnter/blob/master/LICENSE)