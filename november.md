---
layout: default
title: "2024 November"
permalink: /memo/november/
---

※このページは開発者向けのMemoです

**目次**
* TOC
{:toc}

## 猫の様に生きるのは合わなかった

近所の猫をみて思っていたことがある。彼らの様に毎日ダラダラと生きてみたいと。

しかし実際に毎日ダラダラと過ごしてみると何に対してもやる気が起こらなくなった。そして毎日がなんだか虚しくなった。

だから悟った。自分は忙しい方が好きなのだと。

なので忙しく生きてみようと思う。成長もするし。

<br>

## jekyllで新しいファイルを作成した時にリンクさせる方法

「〇〇.md」のファイルを作成したが正しく読み込まれない
* 解決方法
    * 原因
        * baseurlが設定されている
    * 相対パスを使う
    * relative_urlフィルターを使う
        * baseurlや他の設定を考慮したリンクを作成
    * コード例
        * <a href="{{ '/memo/october/' | relative_url }}">October</a>
        * コードはdefault.htmlに記入

## 絶対パス、相対パス
* 絶対パス
    * 完全なURLを使用
* 相対パス
    * 現在位置から相対的にリンクを指定