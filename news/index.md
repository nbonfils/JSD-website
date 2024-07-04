---
title: News
nav:
  order: 7
  tooltip: Latest Updates
---

{% include search-box.html %}

<!-- select tags -->
{% include tags.html tags="python, git, github, testing, linting, data, workflow, packaging" %}

{% include search-info.html %}

{% include list.html data="posts" component="post-excerpt" %}

<!-- all tags -->
{% include tags.html tags=site.tags %}