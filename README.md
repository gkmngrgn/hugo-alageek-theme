# HUGO ALAGEEK THEME

alaGeek is an enhanced version of the
[Cocoa](https://github.com/mtn/cocoa-eh-hugo-theme) theme featuring a customizable
homepage with different sections including the latest posts, syntax highlighting and
MathJax support and much more. It's rewritten with **Bootstrap 5**.

![](/images/screenshot.png)

Websites that are using Hugo with alaGeek theme:

- https://alageek.com
- https://gokmengorgen.net

_Feel free to open a pull-request to add your website here, I'll check this list every
new version. You don't need to use the latest version of the theme._

## FEATURES

- Social media links on the footer:
  - 500px
  - Facebook
  - Flattr
  - GitHub
  - GitLab
  - Linkedin
  - Mastodon
  - Twitter
- Homepage with latest and best posts.
- Single pages, sections with a header and a list of articles
- Syntax highlighting with `highlightjs`
- Progressive images
- Twitter cards support
- LaTeX support with MathJax
- Possibility to add extra scripts with `footer_extra.html`
- Disqus support
- Dark-mode support
- High accessibility score
- Pagination support in blog posts
- General and post-specific Table of Contents support.

## DEPENDENCY VERSIONS

- bootstrap: 5.2.1
- highlightjs: 11.6.0
- mathjax: ^3.0.0
- progressively: latest stable version

## TYPOGRAPHY

You can customize the fonts copying and editing `style_main.html` file. The defaults
are:

- Title: Merriweather Sans
- Content: Merriweather
- Code: Fira Code

## SUPPORTED LANGUAGES

- Catalan
- English (Default)
- Romanian
- Russian
- Spanish
- Turkish

## BACKWARD-INCOMPATIBLE CHANGES

### V3.0.0: REGENERATE PROJECT FROM SCRATCH

- `icon_back.html` has been renamed `icon_prev.html`.
- `header_extra.html` has been renamed `head_extra.html`.
- HEAD tags have been moved to `head.html`.
- All script lines have been moved to `footer_extra.html`.
- `highlight.css` has been removed and a new partial template `style_highlight.html` has
  been created.

### V2.0.0: NEW MARKDOWN PARSERS

If you prefer to use Goldmark instead of Blackfriday for Markdown parser, you need to
set `xhtml: true` for activating `progressively` extension. Also, you need to set
`unsafe: true` if you use Bootstrap HTML components in Markdown files. Please take a
look at [this document](https://gohugo.io/getting-started/configuration-markup/) for
more information.

### V2.0.0: BOOTSTRAP V5 MIGRATION

If you have a Bootstrap v4 specific customization on your theme, please take a look at
[this document](https://getbootstrap.com/docs/5.0/migration/) or keep your theme in the
old version v1.5.0.

## HOW DARK MODE WORKS

It automatically reads your system or browser color scheme and activates the dark or
light mode. If you want to use dark mode in all cases, copy and move the `main.css` into
your static folder keeping the path, remove light-mode specific colors.

## LICENSE

Licensed under the MIT License. See the LICENSE.md file for more details.
