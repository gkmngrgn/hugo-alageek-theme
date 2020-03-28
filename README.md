# hugo-alageek-theme
A [Cocoa Enhaced](https://github.com/mtn/cocoa-eh-hugo-theme) based theme. It's rewritten with **Bootstrap 4**.

![](/images/screenshot.png)

Websites that are using hugo with alaGeek theme:

* https://alageek.com
* https://gokmengorgen.net

## Features

* Social media links on the footer:
    - 500px
    - Facebook
    - Flattr
    - GitHub
    - GitLab
    - Linkedin
    - Mastodon
    - Twitter
* Homepage with latest and best posts.
* Single pages, sections with a header and a list of articles
* Syntax highlighting with `hightlightjs`
* Progressive images
* Twitter cards support
* LaTeX support with MathJax
* Possibility to add extra scripts with `footer_extra.html`
* Disqus support
* Dark-mode support
* High accessibility score
* Pagination support in blog posts
* General and post-specific Table of Contents support.

## Supported Languages

* Catalan
* English (Default)
* Romanian
* Russian
* Turkish

## Dependency versions

* bootstrap: 4.4.1
* highlightjs: 9.15.10
* jquery-slim: 3.4.1
* mathjax: 2.7.5
* progressively: 1.2.5
* popper.js: 1.16.0

## Typography

* Title: Merriweather Sans
* Content: Merriweather
* Code: Fira Code

## Updates

### Goldmark Compatibility

If you prefer to use Goldmark instead of Blackfriday for Markdown parser, you
need to set `xhtml: true` for activating `progressively` extension. Also, you
need to set `unsafe: true` if you use Bootstrap HTML components in Markdown
files. Please take a look at [this
documentation](https://gohugo.io/getting-started/configuration-markup/) for more
information.

## License

Licensed under the MIT License. See the LICENSE.md file for more details.
