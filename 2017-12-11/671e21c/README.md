# JBoss Blog

This is a Jekyll blog. To maintain the blog, it's best you have Ruby installed.
From within Ruby, install Jekyll and Rake too.

```shell
gem install jekyll
gem install rake
```
## Pull requests

Please take ref of these 
* Create your post under `_posts` dirertory, in `yyyy-mm-dd-title.md` format. 
* [posts](https://github.com/jboss-outreach/blog.jboss-outreach.org/tree/master/_posts)
* [pull request](https://github.com/jboss-outreach/blog.jboss-outreach.org/pull/21)

## Setup
* [Linux](https://blog.jboss-outreach.org/support/setup-linux)
* [Eclipse che](https://blog.jboss-outreach.org/support/eclipse-che-setup)

## Creating New Articles

There is a rake task for this -

```
rake new_post["Topic of new post"]
```

## Creating a new page

There is a rake task for this as well -

```
rake new_page["Title of Page"]
```
Set `page.sitemap.include` to `'yes'`, to include the page in sitemap.
```
sitemap:
  include: 'yes'
```


Based on Type Theme by Rohan Chandra
![Default Type Theme blog](https://cloud.githubusercontent.com/assets/816965/5142407/19742e48-71d6-11e4-8d9d-fdfe010784f0.png)

A free and open-source [Jekyll](http://jekyllrb.com) theme. Great for blogs and easy to customize.

## Get Started

[Demo](https://rohanchandra.github.io/type-theme/)

[Using Type](https://rohanchandra.github.io/project/type/)

## License
The MIT License (MIT)
