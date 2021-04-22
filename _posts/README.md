# Auto-convert markdown files To Posts

[`fastpages`](https://github.com/fastai/fastpages) will automatically convert markdown files saved into this directory as blog posts!

You must save your notebook with the naming convention `YYYY-MM-DD-*.md`.  Examples of valid filenames are:

```shell
2020-01-28-My-First-Post.md
2012-09-12-how-to-write-a-blog.md
```

# Resources

- [Jekyll posts](https://jekyllrb.com/docs/posts/)
- [Example markdown post](https://github.com/fastai/fastpages/blob/master/_posts/2020-01-14-test-markdown-post.md)


# Head of posts
```
---
title: "My Title"
description: "Awesome description"
layout: post
toc: false
comments: true
image: images/some_folder/your_image.png
hide: false
search_exclude: true
categories: [fastpages, jupyter]
metadata_key1: metadata_value1
metadata_key2: metadata_value2
---
```
