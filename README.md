# hypocrisy
hypocrisy is a responsive design theme for Hexo.
This theme is based on [Kieran's Blog](http://go.kieran.top)
I changed some css style,
add tags and sitemap in sidebar,
add search on the nav,
add google analytics and fancybox.
and there are some other changes, but i cannot list all.
[Demo| Hypocrisy's Blog](http://hypocrisy.info)
###Install
Execute the following command and modify theme in <code>_config.yml</code> to <code>hypocrisy</code>.
```
git clone https://github.com/hecate-xw/hexo-theme-hypocrisy.git
```
<!--more-->
###Update
Execute the following command to update hypocrisy.
``` 
cd themes/hypocrisy
git pull
```
###Config
####Theme_config.yml
```
cover: /img/bg_img.jpg  #This is no use currently
logo: /img/logo.png
top_saying:
- title: YOU'VE MADE A <span>BRAVE</span> DECISION, WELCOME.
- content: 每一个不曾起舞的日子都是对生命的辜负。
bottom_saying: 虽然还没想好写点什么，但是总觉得这里放句话比较和谐。
  
excerpt_link: Read More
  
rss: /atom.xml
  
highlightjs: vs

works:
- works_name: XXX1
  works_url: /
- works_name: XXX2
  works_url: /
  
duoshuo: duoshuo_name
  
github: https://github.com/
twitter: https://twitter.com/
facebook: https://www.facebook.com/
google:  https://google.com/
weibo: http://weibo.com/
  
timeline:
- num: 1
  word: 2014/06/12-Start xxx
- num: 2
  word: 2014/11/29-Start bbb
- num: 3
  word: 2015/02/18-Start ddd
- num: 4
  word: ...
  
links:
- name: Kieran
  link: http://go.kieran.top/
- name: Name
  link: http://hypocriys.info/
```
####Hexo_config.yml
change some code to enable archives page
```
# Archives
## 2: Enable pagination
## 1: Disable pagination
## 0: Fully Disable
archive: 1
category: 1
tag: 1
```
###Icon
Seclet icon which you like in<code>\hypocrisy\source\css\iconList.css</code>  
![](http://kieran-hexo.qiniudn.com/hexo_14_1.png)  
![](http://kieran-hexo.qiniudn.com/hexo_14_2.png)
###Screen
Show
![](http://kieran-hexo.qiniudn.com/hexo_14_3.png)
  
Content
![](http://kieran-hexo.qiniudn.com/hexo_14_4.png)
###Others
If you like this theme, [Fork](https://github.com/hecate-xw/hexo-theme-hypocrisy/fork) && Star.
Come on.
