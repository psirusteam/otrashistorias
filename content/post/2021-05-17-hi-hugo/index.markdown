---
title: Mi primer post
author: R package build
date: '2021-05-17'
slug: hi-hugo
categories: []
tags: []
subtitle: ''
summary: ''
authors: [Andrés]
lastmod: '2021-05-17T20:26:48-04:00'
featured: no
image:
  caption: ''
  focal_point: ''
  preview_only: no
projects: []
---


```r
library(ggplot2)
oplot <- ggplot(Orange, aes(x = age, 
                   y = circumference, 
                   colour = Tree)) +
  geom_point() +
  geom_line() +
  guides(colour = FALSE) +
  theme_bw()
oplot
```

<img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-1-1.png" width="672" />
