## Install

``` bash
$ hexo init my-blog
$ cd my-blog
$ npm install
$ npm install --save hexo-renderer-jade hexo-generator-feed hexo-generator-sitemap hexo-browsersync hexo-generator-archive
$ git clone https://github.com/stunstunstun/hexo-theme-chiangmai.git themes/chiangmai
```

## Configuration

`_config.yml`

```yaml
theme: chiangmai

# hexo-generator-archive
archive_generator:
    per_page: 0
    yearly: false
    monthly: false
    daily: false
```
## Deploy

```shell
$ hexo clean
$ hexo generate
$ hexo deploy
```

## Update Theme

``` bash
cd themes/chiangmai
git pull
```

## Write Post

### Meta Description

If you want to set meta description information, please set `desc` property and value to each post — the better method is setting default `desc` property to your scaffolds files, just like:

```md
title: How to make integration with Hexo
date: 2016-12-31 14:49:13
desc: Best way to create personal blog
---

## Why Hexo?

```

result:

```html
<meta name="description" content="Best way to create personal blog" />
```

If there is no `desc` property or value, hexo-theme-chiangmai will use `page.title` and `page.author` instead of it.

### H1~H6 Title

In fact, Hexo-theme-chiangmai only support two kinds of titles: h1~h3 belongs to what i called `big title`, and h4~h6 belongs to `small title`, this means that `#` and `###` have the same styles。

Why i do this? I support that an article should be short and clean, don't let visitors spend much time to recognize the blog post structure.

Another reason is that: i don't have met a great styles to distinguish between different kinds of headers.If you have great idea about it, please let me know.

### Preview

If you want to show preview to your visitors, do add HTML comment tag `<!--more-->` before else

```
<!--more-->
```

### Comment Plugin

Hexo-theme-chiangmai support comment plugins: Disqus. please set like this in your `theme/_config.yml`:

```yaml
disqus: holaxapps
```

## Danger Block

Use html tag with special class property to render block:

```html
<div class="tip">
  Be careful!
</div>
```
