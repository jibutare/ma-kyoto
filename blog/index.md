---
layout: default
title: M&amp;Aリポート
---
<div class="uk-section uk-background-primary uk-light uk-height-medium uk-flex uk-flex-center uk-flex-middle uk-text-center uk-padding-large">
  <h1><span uk-icon="icon: file-text; ratio: 2"></span> {{ page.title }}</h1>
</div>
<div class="uk-section">
  <div class="uk-container uk-container-xsmall">
    <ul class="uk-list uk-list-large uk-list-divider">
      {% for post in site.posts %}
      <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
          - {{ post.date | date: "%Y年%m月%d日" }}
      </li>
      {% endfor %}
    </ul>
  </div>
</div>
