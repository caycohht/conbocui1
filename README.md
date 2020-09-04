# [Con bổ củi ](https://caycohoaqua.webflow.io/ ) - Con Bổ củi

[Cây cỏ hoa quả(https://caycohoaqua.com/)]

CON BỔ CỦI - TÁC DỤNG CỦA CON BỔ CỦI (https://caycohoaqua.webflow.io/ ).

con bổ củi còn được gọi là con bửa củi, con bần bật, nhiều nơi còn gọi với tên gọi khác nhau
Con bổ củi có tên gọi như vậy là do khi cầm trên tay thường lấy cái đầu gật gật liên tục, và rất mạnh nên được gọi là con bổ củi




## Features

- Viết gì tùy ý

## Installation & Update

Viết gì thì tùy

## Usage

cứ viết thôi

#### `config.toml` example

tiếp tục viết

# Optional

# If you use googleAnalytics, you set top-level options in config.toml to the beginning of the config file like other top-level options.
googleAnalytics = "UA-XXXXXXXX-XX"

# and disqus too.
disqusShortName = "yourdisqusshortname"

[Author]
  name = "Hugo Author"

[outputs]
  section = ["JSON", "HTML"]

[[params.nav]]
  identifier = "about"
  name = "About"
  icon = "fas fa-user fa-lg"
  url = "/about/"
  weight = 3

[[params.nav]]
  identifier = "tags"
  name = "Tags"
  icon = "fas fa-tag fa-lg"
  url = "tags"
  weight = 3

[[params.nav]]
  identifier = "categories"
  name = "Category"
  icon = "fas fa-folder-open fa-lg"
  url = "categories"
  weight = 3

[[params.nav]]
  identifier = "search"
  name = "Search"
  icon = "fas fa-search fa-lg"
  url = "search"
  weight = 3

[[params.nav]]
  identifier = "archives"
  name = "Archives"
  icon = "fas fa-archive fa-lg"
  url = "archives"
  weight = 3

[params.logo]
  url = "icon.png" # static/images/icon.png
  width = 50
  height = 50
  alt = "Logo"
```

Change favicon(static/favicon.ico) and icon(static/images/icon.png)!

If you don't change them, your favicon and icon are my face :)

#### Search entire blog posts

You should make ```search.md``` in content directory.

```
---
title: "Search"
---

{{<search>}}
```

#### TOC

If you want to use TableOfContent, you need to write words greater than 400, and set `true` frontmatter `toc`.

#### Back To Top Button

If you want to use Back To Top Button, you need to write words greater than 400, and set `true` frontmatter `backtotop`.

#### Archives

If you want archive page, generate `archive.md` file in `content` directory.

```
$ hugo new archives.md
```

```
+++
title: "Archive page"
type: myarchivetype
+++
```

## Frontmatter example

```
+++
title = "Article title here"
date = 2020-02-15T20:00:00+09:00
tags = ["tags here"]
draft = false
toc = false
backtotop = false
disable_comment = true <!-- disable disqus -->
+++

# Title

<!-- when toc is true and post wordcounts is greater than 400 -->

## Contents
```

## Development

1. Install Node.js and npm, the Node.js package manager.

2. The package.json file in your new sub-theme contains the versions of all the Node.js software you need.
  To install them run:

```
$ npm install
```

3. After fixing files in `static` dir, run `build` command to generate `bundle.js`

```
# for development version
$ npm run build-dev

# for production version
$ npm run build-prod
```

## LICENSE

[MIT](./LICENSE).
