Hexo theme: okko
=================

**This hexo theme is modified from Apollo **

##Installation

###Install

``` bash
$ git clone https://github.com/sllt/okko.git themes/okko
```

###Update

``` bash
cd themes/okko
git pull
```

##Configuration

``` yml
# Header
menu:
    Home: /
    Archives: /archives
rss: /atom.xml

# Content
excerpt_link: Read More
fancybox: true

# Miscellaneous
google_analytics:
favicon: /favicon.png
```

- **menu** - Navigation menu
- **rss** - RSS link
- **excerpt_link** - "Read More" link at the bottom of excerpted articles. `false` to hide the link.
- **fancybox** - Enable [Fancybox](http://fancyapps.com/fancybox/)
- **google_analytics** - Google Analytics ID
- **favicon** - Favicon path
