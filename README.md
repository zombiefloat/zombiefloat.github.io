<p align="center">
    <a href="https://github.com/MOxFIVE/hexo-theme-yelee" target="_blank">
        <img src="http://moxfive.github.io/resources/yelee-mockup.jpg">
    </a>
</p>

&emsp;&emsp;Theme **Yelee** relies on [Hexo-Theme-Yilia][1], thanks for the author [Litten][2]. Fix some bugs, change lots of styles, add several features. And then I made the theme. Yelee is mainly designed for fluent text reading. I change styles and add functions, meanwhile, try hard to keep this theme simple, stupid and clear. Theme DEMO: [MOxFIVE's Blog][3]

[1]: https://github.com/litten/hexo-theme-yilia
[2]: https://github.com/litten
[3]: http://moxfive.xyz

<p align="center">
    <img src="https://img.shields.io/badge/Hexo-v3.1%2B-blue.svg">
    <img src="https://img.shields.io/badge/IE-8%2B-red.svg">
    <a href="https://github.com/MOxFIVE/hexo-theme-yelee/releases" target="_blank">
        <img src="https://img.shields.io/github/release/MOxFIVE/hexo-theme-yelee.svg">
    </a>
    <a href="http://moxfive.xyz" target="_blank">
        <img src="https://img.shields.io/badge/DEMO-MOxFIVE's%20Blog-brightgreen.svg">
    </a>
</p>

<p align="center">
    <a href="http://moxfive.xyz" target="_blank">
        <img src="http://moxfive.github.io/resources/yelee-qrcode.png">
    </a>
</p>

<h3 align="center">
    <a href="http://MOxFIVE.coding.me/yelee" target="_blank">
        Yelee 主题使用说明 [简中]
    </a>
    <br>
    <a href="https://github.com/MOxFIVE/yelee" target="_blank">
        文档 GitHub 仓库
    </a>
</h3>
### Installation

<<<<<<< HEAD
```
git clone https://github.com/MOxFIVE/hexo-theme-yelee.git themes/yelee
```

Change theme field in Hexo root's _config.yml file. 

```
theme: yelee
```

### Update

```
cd themes/yelee
git pull
```

### New Features [DEMO](http://moxfive.xyz/yelee/new-features.html)
| - |                En               |
|:-:|:-------------------------------:|
| 1 |  Flexible table of contents      |
| 2 |  Transparent & Random background |
| 3 |  Scrolling button                |
| 4 |  Copyright info.                 |
| 5 |  Post navigation button          |
| 6 |  Site counter                    |
| 7 |  i18n, multi-language          |
| 8 |  Local Site Search           |
| 9 |  Load Comment dynamically    |

### Configuration

#### Internationalization
Use internationalization to present your site in different languages.
=======
Yilia 是为 [hexo](https://github.com/tommy351/hexo) 2.4+制作的主题。
崇尚简约优雅，以及极致的性能。 你可以点击 [我的博客](http://litten.me/) 查看效果。           
 
如果想体验手机浏览效果，可以扫一下二维码：
>>>>>>> litten/master

https://hexo.io/docs/internationalization.html

```yaml
# Hexo Configuration
## Docs: http://hexo.io/docs/configuration.html

# Site
language: en
```

<<<<<<< HEAD
##### Available Languages

| Code           | -                     | -        | Contributor(s) |
|----------------|:-----------------------:|:----------:|:--------------:|
| **en**         | English               | 英语     |     MOxFIVE    |
| **zh-Hans**    | Chinese (Simplified)  | 大陆简体 |     MOxFIVE    |
| **zh-Hant-HK** | Chinese (Traditional) | 港澳繁體 |     MOxFIVE    |
| **zh-Hant-TW** | Chinese (Traditional) | 台灣正體 |     MOxFIVE    |

> **Any Contribution is Welcome！**

#### 0. Post Excerpt
There are two ways to show excerpt in homepage. 
=======
1. 我喜欢简约。所以近期文章，搜索框都拿掉了    
2. 接地气一点。所以用上了jiathis分享，友言评论      
3. 追求移动端的体验
3. 让大家把注意力放到内容上。这是本主题设计初衷      
4. 主题不支持IE6，7，8。以后也不会     
             
## 一、外观

####**常规**

![常规](https://cloud.githubusercontent.com/assets/2024949/19027861/92879edc-8967-11e6-8e60-7987b6507c8d.gif)

####**手机**

![手机](https://cloud.githubusercontent.com/assets/2024949/19027020/1c5b756a-895f-11e6-99bf-ddff9687aee0.gif)   

####**ipad横竖屏切换**

![ipad横竖屏切换](https://cloud.githubusercontent.com/assets/2024949/19026392/e74e1816-8957-11e6-8f08-eac9b3c8c036.gif)                    

## 二、开发者

为了性能和开发工程化考虑，Yilia需要使用webpack进行构建生成。

如果您对主题有一些定制化的需求，请参考wiki[《Yilia源码目录结构及构建须知》](https://github.com/litten/hexo-theme-yilia/wiki/Yilia%E6%BA%90%E7%A0%81%E7%9B%AE%E5%BD%95%E7%BB%93%E6%9E%84%E5%8F%8A%E6%9E%84%E5%BB%BA%E9%A1%BB%E7%9F%A5)

## 三、使用
>>>>>>> litten/master

- a: <!-- more -->

``` diff
title: Hello World
date: 2015-12-03 00:00:00
---
<Excerpt in index> 
+ <!-- more -->
<The rest of contents文>
```
- b: description in Front-matter

``` diff
title: Hello World
date: 2015-12-03 00:00:00
+ description: "Welcome to Hexo! This is your very first post."
---
<Contents>
```

> Description only support plain text

> Set the value of description with quotes to avoid unexpected error `:`



#### 1. About Page:
cd to your hexo folder and run this code:


```
hexo new page about
```

#### 2. Tags Cloud Page:

```
hexo new page tags
```

> Post with several categories [issue#4](https://github.com/MOxFIVE/hexo-theme-yelee/issues/4) 

#### 3. Background image:

Find or change background images in folder: 

> `/yelee/source/background/`

Setting in `themes/yelee/_config.yml`:

`
background_image: 5
`

- Default value is 5, free to modify the number

- "5": show 5 images form bg-1.jpg to bg-5.jpg in `/yelee/source/background/`

- "0": remove background image and use white-gray theme

> [Saving JPEGs for the Web: Setting Photoshop Up for Progressive JPEGs](http://peteschuster.com/2013/01/saving-jpegs-for-the-web-setting-photoshop-up-for-progressive-jpegs/)

> Optimize images with PhotoShop (JPEG, Quality 0, Progressive)

#### 4. Highlight Style:
Set inline_code to style highlight text & Chose a highlight theme for code block.

```
highlight_style:
  #on: true
  inline_code: 1
  code_block: 1
```

Set `on: true` to enable this feature

highlight theme from https://github.com/chriskempson/tomorrow-theme

#### 5. Comment:
Disqus, duoshuo and youyan is supported, enable ONE of them in theme's "_config.yml".


#### 6. Table of Contents:

Remove toc and the button via putting `toc: false` before "---" at [post].md.

Hide toc in default

> Set `toc: false` in `yelee/_config.yml`. 

(*Set `toc: true` in front-matter to show it in certain post*)


#### 7. Copyright info.:

Hide this via putting `original: false` to post's front-matter.

Hide Copyright info. in default

> Set `copyright: false` in `yelee/_config.yml`. 

(*Set `original: true` in front-matter to show it in certain post*)

#### 8. 404 Page:

```
hexo new page 404
```
And then set `permalink: /404` in `/source/404/index.md` front matter.

#### 9. RSS Feed:

Install plugin: [hexo-generator-feed](https://github.com/hexojs/hexo-generator-feed)

#### 10. Sitemap for SEO:

Install plugin: [hexo-generator-seo-friendly-sitemap](https://github.com/ludoviclefevre/hexo-generator-seo-friendly-sitemap)

Baidu: [hexo-generator-baidu-sitemap](https://github.com/coneycode/hexo-generator-baidu-sitemap)

#### 11. Apple Touch icon:

The Path is `/yelee/source/apple-touch-icon.png`

<<<<<<< HEAD
[Recommended size: 180*180](https://realfavicongenerator.net/blog/apple-touch-icon-the-good-the-bad-the-ugly/)
=======
## 四、配置

主题配置文件在主目录下的`_config.yml`，请根据自己需要修改使用。
完整配置例子，可以参考[我的博客备份](https://github.com/litten/BlogBackup)

```
# Header

menu:
  主页: /
  随笔: /tags/随笔

# SubNav
subnav:
  github: "#"
  weibo: "#"
  rss: "#"
  zhihu: "#"
  #douban: "#"
  #mail: "#"
  #facebook: "#"
  #google: "#"
  #twitter: "#"
  #linkedin: "#"

rss: /atom.xml

# 是否需要修改 root 路径
# 如果您的网站存放在子目录中，例如 http://yoursite.com/blog，
# 请将您的 url 设为 http://yoursite.com/blog 并把 root 设为 /blog/。
root: 

# Content
excerpt_link: more
fancybox: true
mathjax: false

# 是否开启动画效果
animate: true

# 是否在新窗口打开链接
open_in_new: false

# Miscellaneous
google_analytics: ''
favicon: /favicon.png

#你的头像url
avatar:

#是否开启分享
share_jia: true
share_addthis: false

#是否开启多说评论，填写你在多说申请的项目名称 duoshuo: duoshuo-key
#若使用disqus，请在博客config文件中填写disqus_shortname，并关闭多说评论
duoshuo: false

# 如不需要，将该项置为false
# 比如
#smart_menu:
#  friends: false

smart_menu:
  innerArchive: '所有文章'
  tagcloud: '标签'
  friends: '友链'
  aboutme: '关于我'

friends:
  友情链接1: http://localhost:4000/
  友情链接2: http://localhost:4000/
  友情链接3: http://localhost:4000/
  友情链接4: http://localhost:4000/
  友情链接5: http://localhost:4000/
  友情链接6: http://localhost:4000/

aboutme: 很惭愧<br><br>只做了一点微小的工作<br>谢谢大家
```


>>>>>>> litten/master
