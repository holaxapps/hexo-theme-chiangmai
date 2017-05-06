
<img src='http://www.chiangmaijointour.com/upload/logo.JPG' height='300' align='right' />

# hexo-theme-chiangmai

hexo-theme-chiangmai is kind of Hexo theme using HTML5, Sass, Jade.
An example page with hexo-theme-chiangmai could be found at the link below.

- http://holaxprogramming.com/

## Install

### Prerequisite

- hexo-renderer-pug
- hexo-generator-feed 
- hexo-generator-sitemap 
- hexo-browsersync 
- hexo-generator-archive

``` bash
$ hexo init my-blog
$ cd my-blog
$ npm install
$ npm install --save hexo-renderer-pug hexo-generator-feed hexo-generator-sitemap hexo-browsersync hexo-generator-archive
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
