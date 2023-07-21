# HUGO

https://gohugo.io/

## 增加新内容

```shell
hugo new posts/my-first-post.md
```

注意将 draft 设置为 false 以发布内容

```markdown
---
title: "My First Post"
date: 2022-11-20T09:03:20-08:00
draft: true
---
## Introduction

This is **bold** text, and this is *emphasized* text.

Visit the [Hugo](https://gohugo.io) website!
```

## 更新网页

commit 之后会由 GitHub action 自动发布

URL： https://njuti.github.io/ 

