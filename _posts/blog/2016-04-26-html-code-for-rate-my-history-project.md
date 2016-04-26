---
layout: post
title: "HTML Code for *Rate My History* Project"
modified:
categories: blog
excerpt:
tags: []
image:
  feature:
date: 2016-04-26T15:39:55-04:00
---

[MathJax](http://www.mathjax.org/) is a simple way of including Tex/LaTex/MathML based mathematics in HTML webpages. To get up and running you need to include the MathJax script in the header of your github pages page, and then write some maths. For LaTex, there are two delimiters you need to know about, one for block or displayed mathematics `\[ ... \]`, and the other for inline mathematics `\( ... \)`.

## What is *Rate My History*?

*Rate My History* was built in a group project with myself and four other 350 classmates.
It is a website where historians and other people in the history-related academia field go to rate historical events and/or individuals.
This site will help history students with deciding whether or not they should do a research paper and/or presentation on that historical event and/or person.

## Contributing to Writing the HTML Code for Rate My History:

~~~
Here is an example MathJax inline rendering \\( 1/x^{2} \\), and here is a block rendering: 
\\[ \frac{1}{n^{2}} \\]
~~~

Here is an example MathJax inline rendering \\( 1/x^{2} \\), and here is a block rendering: 
\\[ \frac{1}{n^{2}} \\]

The only thing to look out for is the escaping of the backslash when using markdown, so the delimiters become `\\[ ... \\]` and `\\( ... \\)` for inline and block maths respectively.
