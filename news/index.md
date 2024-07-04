---
title: News
nav:
  order: 7
  tooltip: Latest Updates
---


{%
  include list.html
  data="posts"
  component="post-excerpt"
%}

<!-- all tags -->
{% include tags.html tags=site.tags %}