---
title: "R Markdown Practice"
author: "Enmian Chang"
date: "1/5/2021"
output: 
  html_document: 
    keep_md: yes
---


# This is my first R Markdown file
## This is my first R Markdown file
### This is my first R Markdown file
This is my first R Markdown file
_This is my first R Markdown file_ 
**This is my first R Markdown file**

[Any site] (https://www.youtube.com/)
[Enmian Chang] (mailto:enmchang@ucdavis.edu)


```r
3*4
```

```
## [1] 12
```

```r
median(4, 5, 5, 5, 6, 7)
```

```
## [1] 4
```

```r
#install.packages("tidyverse")
library("tidyverse")
```


```r
ggplot(mtcars, aes(x = factor(cyl))) +
    geom_bar()
```

![](RMarkdown-Practice_files/figure-html/unnamed-chunk-3-1.png)<!-- -->

