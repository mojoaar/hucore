# Hucore

Humin is a minimal blog theme for [hugo](http://gohugo.io). The theme is based on [Hucore](https://github.com/mgjohansen/hucore).

## Features

* Responsive & minimal design
* Disqus support
* Google Analytics
* Basic [OpenGraph](http://ogp.me/) metadata support
* Option for social sharing icons on posts
* Option for author on posts

## Screenshot

![](https://raw.githubusercontent.com/ritchie46/humin/master/images/screenshot_github.png)

See [kloudcore.com](https://kloudcore.com) for an example of this theme in use.

## Getting Started

Clone this repository to your hugo theme directory.

```
mkdir themes
cd themes
git clone https://github.com/ritchie46/humin.git
```

## Configuration

__[config.toml](https://github.com/mgjohansen/hucore/blob/master/exampleSite/config.toml)__:

```toml
baseurl = "https://example.com"
languageCode = "en"
title = "Humin"
theme = "humin"
copyright = "&copy; 2017 | Follow on <a href=\"https://twitter.com/mgjohansen\" target=\"_blank\">Twitter</a> | <a href=\"https://github.com/mgjohansen/hucore.git\" target=\"_blank\">Hucore theme</a> & <a href=\"http://gohugo.io\" target=\"_blank\">Hugo</a> ♥"
disqusShortname = "shortname"
googleAnalytics = "trackingcode"

[taxonomies]
tag = "tags"
category = "categories"

[params]
description = "Your description here"
keywords = ["keyword 1", "keyword 2", "keyword 3"]
author = "Morten G. Johansen"
sharingicons = true

[params.highlight]
style = "github"
languages = ["go", "dockerfile"]

[[params.social]]
url = "https://github.com/user"
fa_icon = "fa-github"

[[params.social]]
url = "https://gitlab.com/user"
fa_icon = "fa-gitlab"

[[params.social]]
url = "https://twitter.com/user"
fa_icon = "fa-twitter"

[[params.social]]
url = "https://linkedin.com/in/user"
fa_icon = "fa-linkedin-square"

[[params.social]]
url = "/index.xml"
fa_icon = "fa-rss"

[[params.socialshare]]
url = "https://linkedin.com/in/muser"
fa_icon = "fa-linkedin-square"
```

## Credits

Humin is based on [Hucore](https://github.com/mgjohansen/hucore). 
