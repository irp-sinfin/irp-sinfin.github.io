---
layout: home
 "Home"
---

## Latest news

<div class="posts">
  {% for post in site.posts limit:10 %}
    <article class="post" style="margin-bottom: 40px; border-bottom: 1px solid #eee; padding-bottom: 20px;">
      <header class="post-header">
        <h1 class="post-title">
          <a class="post-link" href="{{ post.url | relative_url }}">{{ post.title | escape }}</a>
        </h1>
        <p class="post-meta" style="color: #666;">{{ post.date | date: "%b %-d, %Y" }}</p>
      </header>
      <div class="post-content">
        {{ post.content }}
      </div>
    </article>
  {% endfor %}
</div>

<hr />

<div style="text-align: center; margin: 40px 0; padding: 20px; background: #fdfdfd; border: 1px solid #eee; border-radius: 5px;">
  <h3>Looking for older posts?</h3>
  <p>You can browse all our previous news and events in the full archive.</p>
  <a href="{{ '/archive/' | relative_url }}" style="display: inline-block; padding: 10px 20px; background: #2a7ae2; color: white; text-decoration: none; border-radius: 5px; font-weight: bold;">View Full Archive</a>
</div>
