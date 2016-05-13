---
layout: page
title: Blog
image: https://images.unsplash.com/reserve/LJIZlzHgQ7WPSh5KVTCB_Typewriter.jpg?ixlib=rb-0.3.5&q=80&fm=jpg&crop=entropy&w=1080&fit=max&s=62f592a5fed4e210cb09177cf37f6ee8
---
{% for post in site.posts %}
  {% assign currentdate = post.date | date_to_string %}
  {% if currentdate != date %}
    {% unless forloop.first %}{% endunless %}
    {% assign date = currentdate %}
  {% endif %}
  <li>
    <h2>
      <a href="{{ site.baseurl }}{{ post.url }}">
        <span>{{ post.title }}</span>
      </a>
    </h2>
  </li>

{% endfor %}
