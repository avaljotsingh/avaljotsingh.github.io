---
layout: post
title: Title of the post
date: 2026-01-01 10:00:00-0600
description: One or two sentences shown on the blog index and in link previews.
tags: formal-methods llm
categories: notes
giscus_comments: false
related_posts: false
# toc:
#   sidebar: left
---

Drafts live in `_drafts/` and are not published. Preview them with
`bundle exec jekyll serve --drafts`.

To publish, move this file to `_posts/` and rename it `YYYY-MM-DD-slug.md`.
The date in the filename determines the URL: `/blog/YYYY/slug/`.

## Things you can use

Math is enabled, inline $$e^{i\pi} + 1 = 0$$ and display:

$$
\forall x.\; P(x) \implies Q(x)
$$

Code blocks get syntax highlighting:

```python
def certify(net, spec):
    return abstract_interpret(net, spec)
```

Footnotes[^1], and a table of contents by uncommenting the `toc` block above.

[^1]: Like this.
