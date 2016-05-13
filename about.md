---
layout: page
title: About
image: https://images.unsplash.com/photo-1458640904116-093b74971de9?crop=entropy&fit=crop&fm=jpg&h=1000&ixjsv=2.1.0&ixlib=rb-0.3.5&q=80&w=1925
---

{% comment %}
  This inserts the "about" photo and text from `_config.yml`.
  You can edit it there (jekyll needs restart!) or remove it and provide your own photo/text.
  Don't forget to add the `me` class to the photo, like this: `![alt](src){:.me}`.
{% endcomment %}

{% if site.author.photo %}
  ![{{ site.author.name }}]({{ site.author.photo }}){:.me}
{% endif %}

{{ site.author.about }}

[write something about self]

***

## References

### Design

* Based on [Hyde](http://hyde.getpoole.com/) by [`@mdo`](https://twitter.com/mdo).

### Icons

* [Wreath](https://thenounproject.com/term/laurel-wreath/203146/) by [Nick Abrams](https://thenounproject.com/nabrams/) from the [Noun Project](https://thenounproject.com/).

[usr]: /how-to-find-a-short-username
