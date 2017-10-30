---
layout: page
title: Theme Setup
excerpt: "List the theme info and Things need to tdo"
modified: 2017-10-30T08:44:33-04:00
image:
  feature: so-simple-sample-image-6.jpg
  credit: WeGraphics
  creditlink: http://wegraphics.net/downloads/free-ultimate-blurred-background-pack/
---

This theme is powered by Ruby, Jekyll, Python, etc.

## TODO

Now requires [Jekyll](http://jekyllrb.com/) 3.0. Make sure to run `bundle update` if you aren't on the latest version to update all gem dependencies.

1. [Install Bundler](http://bundler.io) `gem install bundler` and Run `bundle install` to install Jekyll and all dependencies.
2. `_config.yml` needs to be update and maintain regularly.
3. Add navigation.
4. Add my own url, to replace the github.
5. Posts and Blogs not support video yet.
6. Posts and Blogs not support comments yet. Disqus Comments will be enabled. 

## Scaffolding

```bash
Theme/
├── _includes/
|    ├── browser-upgrade.html    # prompt to install a modern browser for < IE9
|    ├── disqus-comments.html    # Disqus comments script
|    ├── feed-footer.html        # post footers in feed
|    ├── footer.html             # site footer
|    ├── head.html               # site head
|    ├── navigation.html         # site top navigation
|    ├── open-graph.html         # meta data for Open Graph and Twitter cards
|    └── scripts.html            # site scripts
├── _layouts/
|    ├── page.html               # single column page layout
|    └── post.html               # main content with sidebar for author/post details
├── _posts/                      # MarkDown formatted posts
├── _sass/                       # Sass stylesheets
├── about/                       # sample about page
├── articles/                    # sample articles category page
├── assets/
|    ├── css/                    # compiled stylesheets
|    ├── fonts/                  # webfonts
|    └── js/
|        ├── _main.js            # main JavaScript file, plugin settings, etc
|        ├── plugins/            # scripts and jQuery plugins to combine with _main.js
|        ├── scripts.min.js      # concatenated and minified _main.js + plugin scripts
|        └── vendor/             # vendor scripts to leave alone and load as is
├── blog/                        # sample blog category page
├── images/                      # images for posts and pages
├── 404.md                       # 404 page
├── feed.xml                     # Atom feed template
├── index.md                     # sample homepage. lists 5 latest posts 
└── theme-setup/                 # theme setup page. safe to remove
```

---

#### Google Analytics and Webmaster Tools

Google Analytics UA and Webmaster Tool verification tags can be entered under `owner` in `_config.yml`. For more information on obtaining these meta tags check [Google Webmaster Tools](http://support.google.com/webmasters/bin/answer.py?hl=en&answer=35179) and [Bing Webmaster Tools](https://ssl.bing.com/webmaster/configure/verify/ownership) support.

