# Developer Guide

This website uses [Jekyll](http://jekyllrb.com) and the [Affiliates for Jekyll](https://bootstrapstarter.com/bootstrap-templates/template-affiliates-bootstrap-jekyll/) theme.

### Quick Start

1. Clone this repo:

    `git clone https://github.com/savedanpovey/savedanpovey.github.io.git`
    
2. Install Ruby and Jekyll by following [this](https://jekyllrb.com/docs/installation/macos/)
3. Build this site locally:
    
    `bundle exec Jekyll build`
    
4. Run this site locally:

    `bundle exec jekyll serve --watch`
    
5. If everything checks out, send me a PR or ask me to add you as a callobrator


References:
* https://help.github.com/en/articles/setting-up-your-github-pages-site-locally-with-jekyll

### Editing

#### Add a page

In root folder, add your .md file just like ``about.md``. Yaml front matter:

```
---
layout: page
title: Affiliates Template for Jekyll
comments: true
---
```

#### Add a post

Start by adding your .md files in ``_posts``. Yaml front matter:

```
---
layout: post
title:  "We all wait for summer"
author: john
categories: [ Jekyll, tutorial ]
image: assets/images/5.jpg
featured: true
---
```

### TODO

- [ ] clean up header and footer
- [ ] clean up featured posts
- [ ] discuss PR plans (both online and offline)

### Original Copyright

Copyright (C) 2019 WowThemes.net.

**Affiliates for Jekyll** is designed by [Sal](https://www.wowthemes.net) and it is licensed MIT. If this project helps you reduce time to develop or you want to remove the attribution credit, you can give me a cup of coffee :)

[Buy theme author a coffee](https://www.wowthemes.net/donate/)

-----------------
