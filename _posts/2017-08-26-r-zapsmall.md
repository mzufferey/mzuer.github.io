---
layout: post
title: "<em>zapsmall</em>: drop values to zero"
date: 2017-08-26
category: R
tags: [R, function]
---

values closed to zero (to a certain number) are treated as zero

```
x1 <- c(52938, 1928, 12, 2, 0.0053)
y  <- c(52938, 1928, 12, 2, 0)
all(zapsmall(x1, 6) - y == 0)
```


<small> viewed on http://www.rfunction.com/ </small>
