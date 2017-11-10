---
layout: post
title: "This is my First Post"
subtitle: "Testing out Blogging with R Markdown"
date: 2017-11-10
categories: rblog
tags: R 
--- 


Hello World
===========

Here is my first try at using [github pages](https://github.io/) and
rmakrdown to blog some of my work. My first few blog posts are going to
be a mess but hopefully over time they will get better :)

Sample Code
===========

R Code
------

    print("Hello World!")

    ## [1] "Hello World!"

Plot
----

    # Creating a Graph
    attach(mtcars)
    plot(wt, mpg) 
    abline(lm(mpg~wt))
    title("Regression of MPG on Weight")

![](first_post_files/figure-markdown_strict/unnamed-chunk-2-1.png)

That's it!
