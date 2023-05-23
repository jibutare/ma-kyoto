---
layout: default
title: 関連レポート&amp;情報
---

<div class="uk-section uk-background-primary uk-light uk-height-medium uk-flex uk-flex-center uk-flex-middle uk-text-center uk-padding-large">
  <h1><span uk-icon="icon: file-text; ratio: 2"></span> {{ page.title }}</h1>
</div>
<div class="uk-section">
  <div class="uk-container uk-container-xsmall">
    <p class="uk-margin-large-bottom"><a
        href="{{ '/ma-guideline' | absolute_url }}">中小 M&amp;A ガイドライン遵守宣誓</a></p>
    <ul class="uk-list uk-list-large uk-list-divider">
      {% for post in site.posts %}
      <li>
        <a href="{{ post.url | absolute_url }}">{{ post.title }}</a>
          - {{ post.date | date: "%Y年%m月%d日" }}
      </li>
      {% endfor %}
    </ul>
  </div>
</div>
