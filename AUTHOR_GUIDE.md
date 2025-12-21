# Author Guide

Welcome to your Digital Garden. This guide explains how to add new content.

## Where to Write

All your writing goes into the `content` folder. Choose the appropriate subfolder:

- **`content/_essays/`**: Long-form structured thinking.
- **`content/_engineering/`**: Technical deep dives, code snippets, and learnings.
- **`content/_reflections/`**: Personal thoughts and philosophy.
- **`content/_journals/`**: Daily logs and quick updates.

## Creating a New Post

1.  Create a new file in the chosen folder.
2.  Name it using the date format: `YYYY-MM-DD-title.md` (e.g., `2025-12-23-learning-rust.md`).
3.  Add the **Frontmatter** at the top of the file:

```yaml
---
layout: post
title: "Your Title Here"
date: 23-12-2025 # Format: dd-mm-yyyy
description: "A short summary for the index page."
status: "seed" # Options: seed, bud, evergreen
---
```

4.  Write your content in Markdown below the dashes.

## Writing Tips
- Use `##` for section headers.
- Use `*italics*` for emphasis.
- Use code blocks for technical details:
  ```javascript
  console.log("Hello World");
  ```
