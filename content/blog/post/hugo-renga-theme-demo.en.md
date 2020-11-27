---
title: "Renga Theme Demo"
author: "Jane Doe"
date: "2018-11-10T12:00:00"
---

[Renga](https://github.com/nanxstats/hugo-renga) is a Bootstrap-based minimalist theme for Hugo.

## Features

- Minimalist
- Responsive & mobile-first (Bootstrap 4)
- Native font stack
- High Contrast
- Math typesetting (MathJaX)
- Syntax highlighting (highlight.js)
- Progressive image loading (progressively.js)
- Disqus
- Google Analytics
- Open Graph meta tags
- Twitter Cards meta tags

## Typography

# h1 Heading

## h2 Heading

### h3 Heading

#### h4 Heading

##### h5 Heading

###### h6 Heading

---

**This is bold text**

__This is bold text__

*This is italic text*

_This is italic text_

~~Deleted text~~

> Block quotes are
> written like so.
>
> They can span multiple paragraphs,
> if you like.

Some text, and some `code` and then a nice plain [link with title](https://nanx.me "title text!").

and then

+ Create a list by starting a line with `+`, `-`, or `*`
+ Sub-lists are made by indenting 2 spaces:
  - Marker character change forces new list start:
    * Ac tristique libero volutpat at
+ Very easy!

vs.

1. Lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa

## Code

Inline `code`

```r
library("oneclust")

set.seed(42)
x <- sample(c(
  rnorm(50, sd = 0.2),
  rnorm(50, mean = 1, sd = 0.3),
  rnorm(100, mean = -1, sd = 0.25)
))

oneclust(x, 3)

## $cluster
##   [1] 3 1 3 2 1 1 1 3 2 3 2 2 3 1 1 1 1 1 2 1 1 1 1 1 2 3 2 2 1 1 1 2 1 1 1 3 1
##  [38] 1 3 1 3 2 1 1 3 2 3 2 1 1 3 3 1 2 3 3 1 1 1 1 3 3 1 1 1 1 1 3 2 2 2 2 2 1
##  [75] 1 2 3 2 1 2 1 3 2 3 1 2 3 1 3 1 1 2 1 1 2 3 3 1 2 3 2 3 1 1 2 1 3 1 1 1 1
## [112] 3 1 1 1 1 1 3 1 2 2 1 1 2 1 1 2 2 2 1 2 1 2 1 3 2 2 1 3 3 2 2 2 1 1 3 1 1
## [149] 3 1 2 3 2 3 1 3 1 2 1 1 2 3 1 2 2 3 2 1 1 3 3 1 1 1 1 3 1 3 1 3 1 2 3 2 1
## [186] 3 1 1 1 1 1 1 1 1 1 2 3 3 1 1
## 
## $cut
## [1]   1 101 152
```
