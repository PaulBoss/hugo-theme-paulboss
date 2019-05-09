# HUGO site / blog theme

A free site / blog theme for [HUGO](https://gohugo.io) made with [Bulma](https://bulma.io) based on [Jeffprod](https://themes.gohugo.io/hugo-blog-jeffprod/).

The layout is pretty much the same as Jeffprod. Layout and look-and-feel is basic Bulma. The templates where mostly created from scratch.

## Features
- Homepage
- Blog
- Main menu autogenereated based on content types
- Header image can be changed per page/post
- Sidebar can be overridden per page, or globally overridden without changing the theme.

## Example config
```
baseURL = "https://bosselaar.net"
languageCode = "en-us"
title = "Paul's site/blog/diary"
theme = "paulboss"
pygmentsCodeFences = true
disableKinds = ["taxonomyTerm"]

[taxonomies]
    tag = "tags"
    archive = "archives"
```


