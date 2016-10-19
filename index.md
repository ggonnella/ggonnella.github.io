---
layout: default
title: Homepage
---

Giorgio Gonnella''s Github bloG

### Links

- [Institutional Homepage][home]
- [Github][github]
- [LinkedIn][linkedin]
- [Twitter][twitter]
- [Disqus][disqus]
- [Google Scholar][gsch]

### Posts [RSS](rss.xml)

<ul class="posts">
  {% for post in site.posts %}
  <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

[home]: http://www.zbh.uni-hamburg.de/gonnella
[github]: https://github.com/ggonnella
[twitter]: https://twitter.com/ggonnella
[gsch]: http://scholar.google.com/citations?user={{ site.scholar_ID }}
[disqus]: http://disqus.com/giorgio_gonnella/
[linkedin]: https://www.linkedin.com/in/giorgio-gonnella-36677620
