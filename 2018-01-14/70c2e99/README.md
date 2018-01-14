# JBoss Blog

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/b2466651fc844fb2a262645ae7d1b117)](https://www.codacy.com/app/aashutoshrathi/blog.jboss-outreach.org?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=jboss-outreach/blog.jboss-outreach.org&amp;utm_campaign=Badge_Grade)


This is a Jekyll blog. To maintain the blog, it's best you have Ruby installed.
From within Ruby, install Jekyll and Rake too, as shown below.

```shell
$ gem install jekyll
$ gem install rake
```
## Pull requests

Please take reference of these 
* Create your post under `_posts` dirertory, in `yyyy-mm-dd-title.md` format. 
* [Posts](https://github.com/jboss-outreach/blog.jboss-outreach.org/tree/master/_posts)
* [Pull requests](https://github.com/jboss-outreach/blog.jboss-outreach.org/pull/21)

*Please make sure that you follow the specified format shown below in your post*

File name: `YYYY-MM-DD-post-title.md`

For example, `2018-01-10-updating-readme.md` would be a valid file name.

Inside the file itself, before writing your blog, paste in the following snippet and fill in all the fields appropriately. Make sure that you add a space ` `   right before you add your information.

```
---
layout: post
title: "[MY POST NAME]"
description: "[POST DESCRIPTION]"
headline: 
modified:
category: personal
tags: []
feature-img: 
mathjax: 
chart: 
author: '[YOUR NAME]'
comments: true
featured: true
---
```

For other examples, navigate to `_posts` and view any of the posts.

## Setup
* [Linux](https://blog.jboss-outreach.org/support/setup-linux)
* [Eclipse che](https://blog.jboss-outreach.org/support/eclipse-che-setup)

## Creating New Articles

There is a rake task for this -

```
$ rake new_post["Topic of new post"]
```

## Creating a new page

There is a rake task for this as well -

```
$ rake new_page["Title of Page"]
```
Set `page.sitemap.include` to `'yes'`, to include the page in sitemap.
```
sitemap:
  include: 'yes'
```


This site is based on the _Type Theme_ by Rohan Chandra
![Default Type Theme blog](https://cloud.githubusercontent.com/assets/816965/5142407/19742e48-71d6-11e4-8d9d-fdfe010784f0.png)

It is a free and open-source [Jekyll](http://jekyllrb.com) theme, great for blogs and easy to customize.

## Get Started

[Demo](https://rohanchandra.github.io/type-theme/)

[Using Type](https://rohanchandra.github.io/project/type/)

## License
The MIT License (MIT)

## Help
If you need any help or are stuck anywhere, feel free to ask a question in [the JBoss GCI chat](https://gitter.im/jboss-outreach/gci).
