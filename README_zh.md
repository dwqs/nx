##NX

基于主题 [landscape-plus](https://github.com/hexojs/hexo-theme-landscape) 的改造，如果你不太熟悉Hexo,可以参考这篇文章：[简洁轻便的博客平台: Hexo详解](http://www.ido321.com/1650.html)

预览：[https://dwqs.github.io](https://dwqs.github.io)

##安装指南

切换到hexo的工作目录，运行下面的命令：

```bash
git clone https://github.com/dwqs/nx.git themes/nx
```

修改全局的`_config.yml`:

```
# Extensions
## Plugins: http://hexo.io/plugins/
## Themes: http://hexo.io/themes/
theme: nx
```
主题还在修改，如果你要更新，可以:
```
cd themes/nx
git pull
```

##配置
主题的配置文件是`nx\_config.yml`：
```
# 导航
menu:
  Home: /
  Archives: /archives

# 导航图标
menu_icon:
  Home: fa-home
  Archives: fa-archive

# 内容
excerpt_link: Read More
fancybox: false
mathjax: false

# 边栏
sidebar: right
widgets:
- category
- tag
- tagcloud
- archive
- recent_posts
- links

# 友情链接
links:
  Author: http://www.ido321.com
  Jiuai Website: http://www.92fenxiang.com
  Front-end Developer Handbook: https://dwqs.gitbooks.io/frontenddevhandbook/content/

# Miscellaneous
google_analytics:
favicon: /favicon.ico
twitter:
google_plus:
fb_admins: 
fb_app_id:

# Disqus
disqus_shortname:

# 百度分享
baidushare: false

# 多说
duoshuo_shortname:

# Footer
isShowFooter: false
```

`Footer` 用于配置是否显示文章的 `<footer>`标签，如果要开启百度分享和评论，要先设置此属性为`true`


