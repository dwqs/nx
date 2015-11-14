## NX

A hexo theme based on [landscape](https://github.com/hexojs/hexo-theme-landscape/) and supported https.

Preview: [https://dwqs.github.io](https://dwqs.github.io)
## Installation
####Install
Switch to your hexo working directory, and run the following command in your terminal:

```bash
git clone https://github.com/dwqs/nx.git themes/nx
```

#### Enable

Modify `theme` setting in `_config.yml` to `nx`.

```
# Extensions
## Plugins: http://hexo.io/plugins/
## Themes: http://hexo.io/themes/
theme: nx
```
####Update
```
cd themes/nx
git pull
```

##Configuration

The default profile of the theme is `nx\_config.yml`：

```
# Header
menu:
  Home: /
  Archives: /archives
  About: /about

# Menu Icon
menu_icon:
  Home: fa-home
  Archives: fa-archive
  About: fa-user

# Content
excerpt_link: Read More
fancybox: false
mathjax: false

# Sidebar
sidebar: right
widgets:
- category
- tag
- tagcloud
- archive
- recent_posts
- links

# Links
links:
  Author: http://ido321.com
  Jiuai Website: http://www.92fenxiang.com
  Front-end Developer Handbook: https://dwqs.gitbooks.io/frontenddevhandbook/content/

# Miscellaneous
google_analytics:
favicon: /favicon.png
twitter:
google_plus:
```

* **menu** - Navigation menu, you need to hexo new page 'about' for the about page.
* **menu_icon** - Navigation icon
* **Links** - Friendly Links
* **excerpt_link** - "Read More" link at the bottom of excerpted articles. false to hide the link.
* **fancybox** - Google Analytics ID
* **favicon** - Favicon path
* **google_analytics** - Google Analytics ID
* **twitter** - Twiiter ID
* **google_plus** - Google Plus ID
* **disqus_shortname** - Disqus ID