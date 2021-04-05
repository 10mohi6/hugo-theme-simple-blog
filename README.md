# simple-blog

simple-blog is a simple blog theme for [hugo](http://gohugo.io/).

![screenshot](https://raw.githubusercontent.com/10mohi6/hugo-theme-simple-blog/master/images/screenshot.png)

## Features

- based on [bootstrap](https://getbootstrap.com/)
- pagination
- tags
- categories

## Installation

```shell
$ git clone https://github.com/10mohi6/hugo-theme-simple-blog themes/simple-blog
```

## Usage

```shell
$ hugo server -t simple-blog
```

## Configuration

config.toml

```toml
theme = "simple-blog"
baseURL = "<your site url>"
title = "<your site title>"
copyright = "© 2020 copyright text."
paginate = 3
languageCode = "en"
DefaultContentLanguage = "en"
enableInlineShortcodes = true
footnoteReturnLinkContents = "^"

[menu]

  [[menu.main]]
    identifier = "about"
    name = "About"
    url = "/about/"
    weight = 10

[taxonomies]
category = "categories"
tag = "tags"

[params]
description = "<your site description>"
```

To add a favicon, place your image in `static/images/favicon.ico`

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
