# hugo-alageek-theme

A [Cocoa Enhaced](https://github.com/mtn/cocoa-eh-hugo-theme) based theme. It's rewritten with **Bootstrap 5**.

![](/images/screenshot.png)

Websites that are using hugo with alaGeek theme:

* https://alageek.com
* https://gokmengorgen.net


## Bootstrap v5 Migration

If you have Bootstrap v4 specific customizations on your theme, please
take a look at [this documentation](https://getbootstrap.com/docs/5.0/migration/)
or keep your theme in the old version v1.5.0.


## How dark mode works?

It automatically reads your system or browser color scheme and
activates the dark or light mode. If you want to use dark mode in all
cases, copy and move the `main.css` into your static folder keeping
the path, remove light-mode specific colors.


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
* Spanish
* Turkish


## Dependency versions

* bootstrap: 5.0.1
* highlightjs: 11.0.1
* mathjax: ^3.0.0
* progressively: 1.2.5


## Typography

You can customize the fonts copying and editing `header_extra.html`
file. The defaults are:

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
