# hexo-theme-iOS7

hexo-theme-iOS7 是为 hexo 制作的主题，风格模仿 iOS7 简约风格， 你可以点击 [我的博客](http://esoftmobile.com) 查看效果。

##配置

主题配置文件在主目录下的`_config.yml`：

```
menu:
  Home: /
  Archives: /archives/
  About: /about/
  Subscribe: /atom.xml

widgets: 
- menu
- weibo
- category
- tagcloud

excerpt_link: Read More

fancybox: true

# 友言评论
UYUserId: xxxxxx

# cnzz统计
cnzzId: xxxxxx

# JiaThis分享
jiathisUUID: xxxxxx

weibo:
	name: xxxxxx
	link: xxxxxx

rss: http://xxx.xxx/atom.xml
```

##TODO
当前对小尺寸移动设备支持不够友好，后期会针对手机设备重新设计一套兼容的主题。