---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: single
---

  {% for post in site.posts %}
  <article>
    <h2>
        {{ post.title }}
    </h2>
    {{ post.content }}
  </article>
{% endfor %}
