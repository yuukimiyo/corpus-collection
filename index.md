---
layout: page
title: コーパスの樹
tagline: 管理人の個人的なコーパスコレクションです
---
{% include JB/setup %}


## ご利用にあたって

このページで紹介しているコーパスは管理人が個人的に収集したものです。
原本に関する情報は各コーパスの説明を参照してください。

ご利用に当たって管理人の許可を得る必要はありません。
ご自身の判断で自由ご利用頂いて構いません。

オリジナルに忠実に収集して掲載しているつもりですが、コピーミスなどがあるかもしれません。
正確さが必要な場合などは原本を参照してください。

誤りや、権利の侵害などに関するご指摘は次のメールアドレスへご連絡ください。

yuuki.miyo[at]gmail.com

（[at]の部分は「@」に置き換えてください）

## 日本語コーパス / Japanese corpus

日本語のコーパスです。

<ul class="posts">
  {% for post in site.posts %}
  <li><h3>戦後の所信表明演説</h3></li>
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

This theme is still unfinished. If you'd like to be added as a contributor, [please fork](http://github.com/plusjade/jekyll-bootstrap)!
We need to clean up the themes, make theme usage guides with theme-specific markup examples.


