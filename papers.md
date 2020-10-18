---
layout: page
title:  Publications
cover:  false
menu:   true
order:  1
---

<ul>
{% for paper in site.data.papers.papers %}
  <li>
  {% include paper.html paper=paper %}
  </li>
{% endfor %}
</ul>

See the complete list in: [Google Scholar](https://scholar.google.com/citations?user=P5-SRqUAAAAJ), [ACL Anthology](https://www.aclweb.org/anthology/people/a/arturo-oncevay/) and [Semantic Scholar](https://www.semanticscholar.org/author/Arturo-Oncevay/65775345)
