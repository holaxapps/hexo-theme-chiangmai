
<h1 align="center">
  hexo-theme-chiangmai
</h1>

<div align="center">
  <em>hexo-theme-chiangmai is kind of Hexo theme using HTML5, SCSS, Pug, Gulp. An example page with hexo-theme-chiangmai could be found at the below.</em>
  <br/>
  <em>https://www.holaxprogramming.com/</em>
</div>

<br>
<br>
<br>
<br>

<div align="center">
  <img src='http://www.chiangmaijointour.com/upload/logo.JPG' height='240'/>
</div>

## Install

### Prerequisite Modules

- [hexo-generator-feed](https://github.com/hexojs/hexo-generator-feed)
- [hexo-generator-archive](https://github.com/hexojs/hexo-generator-archive)
- [hexo-generator-sitemap](https://github.com/hexojs/hexo-generator-sitemap)
- [hexo-renderer-pug](https://github.com/maxknee/hexo-render-pug)
- [hexo-browsersync](https://github.com/hexojs/hexo-browsersync)

``` bash
$ hexo init my-blog
$ cd my-blog
$ npm install
$ npm install --save hexo-renderer-pug hexo-generator-feed hexo-generator-sitemap hexo-browsersync hexo-generator-archive
$ git clone https://github.com/stunstunstun/hexo-theme-chiangmai.git themes/chiangmai
```

### Install and build

``` bash
$ cd themes/chiangmai
$ yarn install
$ yarn build
```

## Configuration Theme

You can configure theme by `_config.yml`

`examples`
- https://github.com/holaxapps/holaxprogramming.com/blob/master/_config.yml

```yaml
theme: chiangmai

# hexo-generator-archive
archive_generator:
    per_page: 0
    yearly: false
    monthly: false
    daily: false
```

## Configuration Theme Details

You can configure details `./theme/chiangmai/_config.yml`

`Examples`

```
menu:
    Archives: /archives/
    LinkedIn: ${URL}
# Site Images
favicon: /favicon.ico
logo: /logo.png
# Profiles
profile: /image/profile.jpg
profile_url: ${URL}
# Google Analytics
ga: ${YOUR_GA_ID}
fb:
# Facebook App Id for Comments
    app_id: ${YOUR_FB_APP_ID}
# Facebook Page URL
    fb_page: ${URL}
# Copyright Infomation
startyear: 2012
```

## Update Theme

``` bash
$ cd themes/chiangmai
$ git pull
```

## License

```
The MIT License (MIT)

Copyright (c) 2017 Minhyeok Jung

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
