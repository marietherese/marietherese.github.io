---
layout: post
title:  "About precompiling css"
date:   2017-11-08 19:16:59 +0100
categories: jekyll update
excerpt_separator: <!--more-->
---

## What do you think of pre-compiling your CSS?
In this site Sass is used as a precompiler of the CSS-code. I think Sass made it more fun and easier to work with CSS because of more overview and structure. 

<!--more--> 
## Compare to regular CSS
Compared to regular CSS Sass allows for some extra features like:
* Variables - creates variables that can be used throughout th style sheet.
* Nesting - allows you to write css code in more readable form
* Partials - write css in separate documents starting with an underscore to make modules of css that is easier to maintain
* Import - imports your partials to the main scss file
* Mixins - creates groups of CSS declarations
* Extend - a way to make let selectors in css inherit properties from another selector - that keeps the css DRY
* Operators - you can to math in Sass 

## Which techniques did you use?
In this project I imported all the files from the standard theme in Jekyll and started to transform them to my liking. All the above features where already in use in the code, but my self I changed or implemented variables, nesting, extend and an operator. 

## Pros and cons?
There is mostly pros in using preprocessed css - mainly because that you can keep your css DRY. You have to write less code and therefore it is easier to read and maintain. On top of that the modularization makes it even easier to read and get an overview of.

The use of variables in combination with operators is very effective and makes it takes less time to experiment with different looks.

Among the disadvantages may be the fact that the preprocessor means the use of one more tool. 

It makes the css-code harder to debug due to that the css in the browser does not look the same or have the same number of rows as in the file structure of the scss. 

Pre compiling also means that you have to compile before you can view the result in the browser which might take a little longer. 

But in conclusion the pros vastly exceed the cons.


