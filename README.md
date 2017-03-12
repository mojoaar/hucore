# Hucore

Hucore is a minimal blog theme for [hugo](http://gohugo.io). The theme is based on [Hemingway2](https://github.com/beli3ver/hemingway2.git).

## Features

* Responsive & minimal design
* Disqus support
* Google Analytics
* Basic [OpenGraph](http://ogp.me/) metadata support
* Option for social sharing icons on posts
* Option for author on posts

## Screenshot

![](https://raw.githubusercontent.com/mgjohansen/hucore/master/images/screenshot_github.png)

See [kloudcore.com](https://kloudcore.com) for an example of this theme in use.

## Getting Started

Clone this repository to your hugo theme directory.

```
mkdir themes
cd themes
git clone https://github.com/mgjohansen/hucore.git
```

## Configuration

Take a look in the [exampleSite](https://github.com/mgjohansen/hucore/tree/master/exampleSite) folder.

This directory contains an example config file and the content for the demo.
It serves as an example setup for your documentation.

Copy the `config.toml` in the root directory of your website. Overwrite the existing config file if necessary.

__[config.toml](https://github.com/mgjohansen/hucore/blob/master/exampleSite/config.toml)__:

```toml
baseurl = "https://example.com"
languageCode = "en"
title = "Hu | Core"
theme = "Hucore"
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
url = "https://github.com/mgjohansen"
fa_icon = "fa-github"

[[params.social]]
url = "https://gitlab.com/mgjohansen"
fa_icon = "fa-gitlab"

[[params.social]]
url = "https://twitter.com/mgjohansen"
fa_icon = "fa-twitter"

[[params.social]]
url = "https://linkedin.com/in/mgjohansen"
fa_icon = "fa-linkedin-square"

[[params.social]]
url = "/index.xml"
fa_icon = "fa-rss"

[[params.socialshare]]
url = "https://linkedin.com/in/mgjohansen"
fa_icon = "fa-linkedin-square"
```

## Build

```
hugo server
```

You can go to localhost:1313 and this theme should be visible.

## License

Hucore is licensed under the [MIT License](LICENSE.md).

## Author

[Morten G. Johansen](https://github.com/mgjohansen)

## Credits

Hucore is based on [Hemingway2](https://github.com/beli3ver/hemingway2.git) created by [Malte Kiefer](https://github.com/beli3ver).