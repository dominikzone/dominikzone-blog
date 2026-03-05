---
title: "Testing AI Capabilities: A Blog Cleanup and Content Generation Experiment"
date: 2026-03-05
draft: false
description: "How I used an AI assistant to remove three old blog posts and generate a new post—a short experiment in content cleanup and AI-driven writing with Cursor and Hugo."
showComments: true
tags: ["ai", "cursor", "hugo", "blog", "automation", "content"]
---

A short experiment: I asked an AI assistant to clean up my blog and then write a new post about it. Here’s what happened.

## The task: remove three posts

I gave a single instruction: delete all existing posts. The assistant identified the three posts in my Hugo `content/posts` folder and removed them.

These were the posts that were removed:

| # | Post title                    | Filename                 |
|---|-------------------------------|--------------------------|
| 1 | Welcome on my blog            | `welcome.md`             |
| 2 | VS Code GitPush Test          | `git_vscode_test.md`     |
| 3 | Test Open Interpreter         | `test-open-interpreter.md` |

After that, the `content/posts` directory was empty and ready for new content.

## Why I asked for this post

Once the cleanup was done, I asked the same AI to write a **new post** that would:

1. Describe the cleanup task (and list the removed posts in a small table).
2. Explain that the goal was to **test its capabilities**—both for following instructions (deleting files) and for generating structured content (this article).

So this post is both the result of that test and a short record of how it was done.

## What I was testing

I wanted to see whether the assistant could:

- **Follow multi-step instructions**: delete specific files, then create one new file.
- **Respect conventions**: use proper Hugo front matter, a clear structure, and sensible SEO (title, description, tags).
- **Produce readable content**: write in clear English and include the requested table and context.

If you’re reading this, the experiment worked: the old posts are gone, and this new post was generated and saved in place.

## Takeaways

- A single, clear prompt was enough to trigger both the cleanup and the request for this follow-up post.
- Stating the purpose (“to test your capabilities”) helped shape the kind of post I wanted—meta and explanatory rather than generic.
- For a Hugo blog, specifying “SEO and Hugo rules” in the prompt led to appropriate front matter and structure without extra back-and-forth.

If you use an AI assistant for your own blog or docs, similar small experiments—delete a few items, then generate one new piece of content—are a good way to see how it behaves with your stack and your style.
