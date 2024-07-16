---
title:       "Obsidian carryover?"
subtitle:    ""
description: "If this works, then I'll use Obsidian as an md editor"
date:        2024-06-04
author:      "Nate"
image:       ""
tags:        ["Organization", "Programming"]
categories:  ["Organization"]
---

Following this video: https://www.youtube.com/watch?v=LIFvgrRxdt4

```
> cd https://github.com/Natnater/Blog.git
> cd Blog
> hugo new site Natnater
> cd Natnater
```
I ran into an issue with the config file "hugo.toml" in which I attempted to name my blog "Natnater's Blog."  The issue arose because I coded the config like this:
```
> title = 'Natnater's Blog'
```
instead of this:
```
> title = "Natnater's Blog"
```
## New Post
To make a new post, from the main git page "\\NBlog\\Natnater" I type:
```
> hugo new content content/posts/hello-world.md
```

## Cloudflare
I had to add an environment variable: HUGO_VERSION = 0.128.2 to match the version I found via typing ```hugo version``` into cmd.  This allowed Hugo to build, whereas before it was not, for some reason.  It works!  https://www.Natnater.com.
