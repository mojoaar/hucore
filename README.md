# Hemingway2

Hemingway2 is a really minimal blog theme for hugo.

![](https://github.com/tanksuzuki/hemingway/blob/master/images/tn.png)

## Getting Started

Clone this repository to your hugo theme directory.

```
mkdir themes
cd themes
git clone https://github.com/beli3ver/hemingway2.git
```

## Configuration

Take a look in the [exampleSite](https://github.com/beli3ver/hemingway2/tree/master/exampleSite) folder.

This directory contains an example config file and the content for the demo.
It serves as an example setup for your documentation.

Copy the `config.toml` in the root directory of your website. Overwrite the existing config file if necessary.

__[config.toml](https://github.com/beli3ver/hemingway2/blob/master/exampleSite/config.toml)__:

```toml
baseurl = "https://example.com"
languageCode = "en"
title = "Hemingway2"
theme = "hemingway2"
copyright = "&copy; <a href=\"https://github.com/beli3ver\">Malte Kiefer</a> 2016"
disqusShortname = "shortname"
googleAnalytics = ""
description = "Your personal description"
keywords = ["keyword1", "keyword2"]

[taxonomies]
tag = "tags"
category = "categories"

[params]

[params.highlight]
style = "github"
languages = ["go", "dockerfile"]

[[params.social]]
url = "https://github.com/beli3ver"
fa_icon = "fa-github"

[[params.social]]
url = "https://gitlab.com/beli3ver"
fa_icon = "fa-gitlab"

[[params.social]]
url = "https://twitter.com/malkie16"
fa_icon = "fa-twitter"

[[params.social]]
url = "https://telegram.me/beli3ver"
fa_icon = "fa-telegram"

[[params.social]]
url = "/index.xml"
fa_icon = "fa-rss"
```

## Build

```
hugo server
```

You can go to localhost:1313 and this theme should be visible.

## License

Hemingway2 is licensed under the [MIT License](LICENSE.md).

## Author

[Malte Kiefer](https://github.com/beli3ver)
