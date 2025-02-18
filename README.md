このページは、Jekyllがどのようなものかを確かめるために作成しました。  
テーマには[Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/)を使用しています。


# 記事一覧

{% for post in site.posts %}
<li>
<a href="{{ post.url | relative_url }}">
{{ post.title }}
</a>
<small>（{{ post.date | date: "%Y-%m-%d" }}）</small>
</li>
{% endfor %}