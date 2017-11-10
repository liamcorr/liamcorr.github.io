---
layout: post
title: "This is my First Post"
subtitle: "Testing out Blogging with R Markdown"
date: 2016-12-01
categories: rblog
tags: R 
--- 


-   [Hello World](#hello-world)
-   [Sample Code](#sample-code)
    -   [R Code](#r-code)
    -   [Plot](#plot)

<!-- 
This is the heading that gets added to a .md file after it is made

---
layout: post
title: "This is a test post for my R blog"
date: 2016-12-01
categories: rblog
tags: R 
--- 

-->
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
