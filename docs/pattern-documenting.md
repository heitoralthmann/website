---
layout: docs
title: Documenting Patterns | Pattern Lab
heading: Documenting Patterns
---

Pattern documentation gives developers and designers the ability to provide context for their patterns. The documentation file consists of Markdown with YAML front matter. It should follow this format:

```
---
title: Title for my pattern
---
This is a *Markdown* description of my pattern.
```

The `title` attribute is used in Pattern Lab's navigation as well as in the styleguide views. The `description` is used in the styleguide views.

Pattern documentation needs to have a `.md` file extension and match the name of the pattern it's documenting. For example, to document the following pattern:

    00-atoms/images/landscape-16x9.mustache

We'd name our documentation file:

    00-atoms/images/landscape-16x9.md

## Adding More Attributes to the Front Matter

A future update of Pattern Lab will support more front matter attributes including: state, order, hidden, links and tags.
It will also support adding custom attributes that could be utilized by plugins. For example, GitHub issues related to patterns.
