---
widget: pages
headless: true
weight: 40

title: News
subtitle: Recent updates and highlights

content:
  filters:
    folders:
      - news
  count: 3
  offset: 0
  order: desc

design:
  view: compact
  columns: "1"
---

<style>

/* Pull the first news item closer to the heading */
#news .stream-item:first-of-type {
  margin-top: -2.5rem !important;
}

/* Reduce spacing between news items */
#news .stream-item {
  margin-bottom: 0.8rem !important;
}

#news .article-title {
  margin-bottom: 0.15rem !important;
}

#news .article-style {
  margin-bottom: 0.15rem !important;
}

#news .stream-meta {
  margin-top: 0.15rem !important;
  margin-bottom: 0 !important;
}

</style>