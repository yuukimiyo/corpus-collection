---
layout: post
title: "国会演説コーパス（戦後の所信表明演説）"
description: "戦後の歴代首相による所信表明演説を収録しています。"
comments: false
category: Japanese
tags: ["国会演説"]
---
{% include JB/setup %}

## 概要

This is the corpus of Japanese Text that general policy speech of prime minister of japan.
(from 1953 to 2014)

戦後（1953～2014）の歴代首相による所信表明演説のコーパスです。

## 原本

Wikipediaの「所信表明演説」から戦後の歴代首相が所信表明演説を行った国会回次と日付を調べ、国会会議録検索システムで該当回次と首相名で検索して表示された演説を収集しました。

## データの性質

127回国会では発言者によって１回中断し、データが分かれているが、続行分を加えて１つにして作成している。
この際（もとデータでは総理発言が「(発言者あり)」という形で途切れ、別項目で行頭が「内閣総理大臣(○○君)(続)」となって再開しているが、この行頭部分は削除した。）

174回国会では発言者によって２回中断し、データが分かれているが、それぞれ続行分を加えて１つにして作成している。
（処理方法は127回国会と同様）

178回国会では発言者によって２回中断し、データが分かれているが、それぞれ続行分を加えて１つにして作成している。
（処理方法は127回国会と同様）

総理大臣の名前の字体がWikipediaと国会会議録検索システムとで違うケースがあったが、全てそのままにしている。
(例, Wiki:宮沢喜一, 議録：宮澤喜一)

## フォルダ構成

    .
    |-- longfilename
    |   |-- sjis
    |   |   |-- ...
    |   |-- utf8
    |   |   |-- ...
    |-- shortfilename
    |   |-- sjis
    |   |   |-- ...
    |   |-- utf8
    |   |   |-- ...

## ダウンロード

[https://github.com/yuukimiyo/GeneralPolicySpeechOfPrimeMinisterOfJapan/archive/master.zip](https://github.com/yuukimiyo/GeneralPolicySpeechOfPrimeMinisterOfJapan/archive/master.zip)

