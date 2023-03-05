---
title: "Welcome"
linkTitle: "Site"
type: "docs"
# tags: ["intro"]
weight: 20

cascade:
- _target:
    path: "/blog/**"
  type: "blog"
  # set to false to include a blog section in the section nav along with docs
  toc_root: true
- _target:
    path: "/**"
    kind: "page"
  type: "docs"
- _target:
    path: "/**"
    kind: "section"
  type: "docs"
- _target:
    path: "/**"
    kind: "section"
  type: "home"
---

{{% pageinfo %}}
This is a placeholder page that shows you how to use this template site.
{{% /pageinfo %}}

This is the landing page content for the home page.
