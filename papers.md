---
layout: page
title:  Selected publications
cover:  false
menu:   true
order:  1
---

Full list in: [Google Scholar](https://scholar.google.com/citations?user=P5-SRqUAAAAJ), [ACL Anthology](https://www.aclweb.org/anthology/people/a/arturo-oncevay/) or [Semantic Scholar](https://www.semanticscholar.org/author/Arturo-Oncevay/65775345)

<ul>
{% for paper in site.data.papers.papers %}
  <li>
  {% include paper.html paper=paper %}
  </li>
{% endfor %}
</ul>
