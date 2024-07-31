---
title: An Example Post
subtitle: Listen, I'm new to this
description: In Which I Test Some Markdown
date: 2024-07-31
author: Nate
image: ""
tags:
  - Blog
  - code
  - programming
  - organization
categories:
  - Tech
layout: post
---
# Prologue
Just testing some markdown stuff to see how it works with Hugo.  May delete this later, or may keep it as a reference.

For the record, I write my Markdown in Obsidian so I get a bit of a WYSIWYG thing going on -- I know the whole point of Markdown is that it's supposed to be readable on its own, but hey -- don't judge me :)

One of these days I'll learn some HTML.  I must be the only Hugo-based blog on the net being run by someone who doesn't come from a web design background (at least from what I've seen).

# Tests
Obviously I have headers figured out.
``` Headers
# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6

Alt Header 1
---

Alt Header 2
===
```
# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6

Alt Header 1 (three -)
---
Alt Header 2 (two -)
--

Alt Header 3 (three =)
===
Alt Header 4 (two =)
==


```
line break
---
```
---

``` Quotes
> Hello
> There
```
> Hello
> There

>Nesting
> >Quotes
> > >Is 
> > > > Fun
> > > Yes
> > It
> Is

```Tags
#Tags
(might just be an obsidian thing)
```
#Blog 

```External Links
[External Link](http://example.com/)
[example] [id]
[^id]: http://example.com/ "Title"

Text[^2]
[^2]:http://example.com/
```
[External Link](http://example.com/)

[example] [id]
[^id]:http://example.com/ "a test"

Text[^2]
[^2]:http://example.com/

```External Link 2
[Natnater](http://Natnater.com/ "A great blog") <- hover over link

<http://Natnater.com>
```
[Natnater](http://Natnater.com/ "A great blog")
<http://Natnater.com>

[Heading ID](#Header 1)

### Internal Links
```internal_links
[Photo Session 1](/post/photo_session_one/photo_session_one.md)

[Photo Session 1](/content/post/photo_session_one/photo_session_one.md)

[Photo Session 1](content/post/photo_session_one/photo_session_one.md)

```
[Photo Session 1](/post/photo_session_one/photo_session_one.md)

[Photo Session 1](/content/post/photo_session_one/photo_session_one.md)

[Photo Session 1](content/post/photo_session_one/photo_session_one.md)

### Definition List

First term
: This is the definition of the first term.

Second Term
: This is one definition.
: This is another.

```footnotes
[^3]footnote paragraph
	plz
```

	[^3]:footnote paragraph plz

	Code block (just indent)
	print("hello world")

`surround word with single backtick for inline code` like this

```Title
triple backticks for longer code blocks like this, with a title at the end of the first set of backticks
```

```python
print("instead of a title, use the name of a programming / scripting language to get colors out of it")
```

```C
for i == 2{
	x = "I don't like C"
}
```

```Formatting
**BOLD**
*ITALIC*
~~STRIKETHROUGH~~
==HIGHLIGHT==
~~==***ALL OF THE ABOVE==***~~
```
**BOLD**
*ITALIC*
~~STRIKETHROUGH~~
==HIGHLIGHT==
~~==***ALL OF THE ABOVE==***~~

```Subscript
H~2~O
X^2^
X^2
```
H~2~O
X^2^
X^2


### Task list
``` Task List
- [ ]Task 1
- [x] Task 2 
- [?] Task 3
- [*] Task 4
- [ ] Task 5
```
- [ ] Task 1
- [x] Task 2 
- [?] Task 3
- [*] Task 4
- [ ] Task 5

# Interlink

![webcomics post](August24/August24)
### Table

```Table

| Header 1 | Header 2 |
| -------- | -------- |
| Cell 1   | Cell 2   |
|          | Cell 4   |

```

| Header 1 | Header 2 |
| -------- | -------- |
| Cell 1   | Cell 2   |
|          | Cell 4   |


