---
title: "Sample post: how writing works here"
description: "A draft that shows the formatting. Delete it once your first real post is up."
date: 2026-10-20
tags: [meta]
draft: true
---

This is a **draft**. Drafts show up while you run the site locally (`npm run dev`), but they're left out of the published site. Set `draft: false` (or remove the line) to publish.

## Writing a post

Create a Markdown file in `src/content/blog/`. The file name becomes the URL, so `my-first-post.md` is published at `/writing/my-first-post/`.

Each post starts with a small header:

```yaml
---
title: "What a view reads decides what re-renders"
description: "One sentence. Shown in lists, search results and link previews."
date: 2026-10-21
tags: [swiftui, performance]
---
```

## Formatting

Regular Markdown works: *emphasis*, [links](https://mfsaglam.github.io), lists, quotes and code.

> A short quote looks like this.

```swift
@Observable final class MapState {
    var sheetHeight: CGFloat = 0
}
```

- Lists work
- Like this

Images go in `public/` and are referenced as `/my-image.jpg`.
