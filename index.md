---
layout: default
title: Homepage
---

### Links

- [Institutional Homepage][home]
- [Github][github]
- [Twitter][twitter]
- [Disqus][disqus]
- [Google Scholar][gsch]

### Posts [RSS](rss.xml)

<ul class="posts">
  {% for post in site.posts %}
  <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

[home]: http://zbh.uni-hamburg.de/gonnella
[github]: https://github.com/ggonnella
[twitter]: https://twitter.com/ggonnella
[gsch]: http://scholar.google.com/citations?user={{ site.scholar_ID }}
[disqus]: http://disqus.com/giorgio_gonnella/
