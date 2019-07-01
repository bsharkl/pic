# 这个我的一个图床系统


---

## 关于GitHub

GitHub是一个面向开源及私有软件项目的托管平台，因为只支持git 作为唯一的版本库格式进行托管，故名GitHub，付费用户可以建私人仓库，我们一般的免费用户只能使用公共仓库，也就是代码要公开

Github 由Chris Wanstrath, PJ Hyett 与Tom Preston-Werner三位开发者在2008年4月创办，主要提供基于git的版本托管服务

## 今天，GitHub已是

*   一个拥有143万开发者的社区。其中不乏Linux发明者Torvalds这样的顶级黑客，以及Rails创始人DHH这样的年轻极客。
*   这个星球上最流行的开源托管服务。目前已托管431万git项目，不仅越来越多知名开源项目迁入GitHub，比如Ruby on Rails、jQuery、Ruby、Erlang/OTP；近三年流行的开源库往往在GitHub首发，例如：BootStrap、Node.js、CoffeScript等。
*   alexa全球排名414的网站

## 注册账户

想要使用GitHub来做我们的免费图床当然是先去注册[GitHub](https://github.com/)之后就可以创建你的免费仓库了

## 创建仓库

1.  点击网站的New Repository
    [![1.png](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780418.png "1.png")](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780418.png)
2.  输入仓库的名字，仓库描述，选择“Public”,然后勾选下面的“Initialize this repository with a README”
    [![2.png](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780419.png "2.png")](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780419.png)
3.  上面的步骤操作完成后点击“Create repository”创建完成后你会看到这样的一个界面，上面有你之前设置的仓库名字和描述
    [![3.png](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780421.png "3.png")](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780421.png)
4.  点击“Settings”
    [![4.png](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780422.png "4.png")](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780422.png)
5.  往下拉，找到“GitHub Pages”板块，点击“choose a theme”
    [![5.png](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780423.png "5.png")](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780423.png)
6.  选择默认的即可，直接点击“Select theme”
    [![6.png](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780426.png "6.png")](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780426.png)
7.  选择完毕之后，会自动跳转，能看到刚刚页面的代码(总之，看到第一行是## Welcome to GitHub Pages就差不多了)
    [![7.png](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780427.png "7.png")](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780427.png)
8.  继续点击“Settings”，找到“GitHub Pages”板块，我们去看看刚刚页面的网址
    [![8.png](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780428.png "8.png")](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780428.png)
9.  打开(只是打开看看，这一步做不做无所谓)
    [![9.png](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780430.png "9.png")](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780430.png)
10.  接下来我们去自定义我们的域名，输入名字，然后接你的域名
    [![10.png](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780431.png "10.png")](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780431.png)
11.  点击“Save”，然后复制一下534119219.github.io(每个人的都不一样，都是你的账号+.github.io)
    [![11.png](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780433.png "11.png")](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780433.png)

## 域名绑定

我们需要把域名解析到刚刚复制的那个记录值上，才能以外链的形式访问我们的仓库

1.  添加解析，记录类型：CNAME；主机记录：test.skaberen.com(刚刚自定义的域名)，解析线路默认，记录值填写刚刚复制的
    [![12.png](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780434.png "12.png")](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780434.png)
2.  域名解析完毕之后，测试下能不能正常访问自定义的域名
    [![13.png](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780436.png "13.png")](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780436.png)

至此，域名已经成功解析，只剩下上传文件了

## 上传文件

1.  点击“Your profile”
    [![14.png](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780437.png "14.png")](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780437.png)
2.  点击刚刚创建的仓库
    [![15.png](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780439.png "15.png")](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780439.png)
3.  点击“Open in Desktop”，如果你已经安装了桌面程序，这一步将会直接启动你的桌面程序
    [![16.png](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780441.png "16.png")](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780441.png)
4.  登录你的GitHub帐号，选择第三个“Clone repository ”
    [![18.png](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780445.png "18.png")](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780445.png)
5.  将仓库克隆到本地
    [![19.png](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780447.png "19.png")](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780447.png)

克隆中
[![20.png](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780448.png "20.png")](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780448.png)

1.  克隆完成之后，看看本地是不是有了你GitHub的仓库文件了，默认保存在我的文档/GitHub/(你的仓库名)中
    [![21.png](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780449.png "21.png")](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780449.png)
2.  你可以在这个仓库中新建文件夹，也可以直接复制文件进去
    [![22.png](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780450.png "22.png")](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780450.png)

[![23.png](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780452.png "23.png")](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780452.png)

1.  文件复制进去之后，就能在软件这边看到了，一般输入摘要就好了，描述可以留空，然后点击“Commit to master”
    [![24.png](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780453.png "24.png")](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780453.png)
2.  点击“Push origin”，这一步就是将你的文件上传到GitHub中
    [![25.png](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780455.png "25.png")](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780455.png)
3.  上传完成之后，在去浏览器刷新一下，就能看到你刚刚上传的文件了
    [![27.png](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780457.png "27.png")](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780457.png)
4.  至此，我们已经能够通过外链访问我们上传的文件了
    在浏览器输入文件路径即可

[![28.png](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780458.png "28.png")](https://skaberen-1252068621.cos.ap-chengdu.myqcloud.com/2018/11/21/1542780458.png)

最后修改：2018 年 11 月 21 日 02 : 09 PM
