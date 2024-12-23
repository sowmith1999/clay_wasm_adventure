# CLAY WebApp

This is me trying me out how to write a webapp with the github.com/nicbarker/clay as the
layout tool, instead of CSS or something.

The high level flow here is, I describe the how I want my UI to interact and what not,
basically the front end in main.c, which is written with CLAY macros and functions.

Which then compiles into WASM, and then bundled with a index.html that contains the html
renderer. This HTML renderer, I don't think is a core part of the library, at it core, it only
does layout computation.

I am interested in this because, I don't like writing CSS and JS, and they seem too
complicated. Here I will try and write a page for my blog.
