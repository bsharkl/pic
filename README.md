# 这个我的一个图床系统


一次偶然的机会让我接触到Markdown语法，随后便疯狂地爱上了这种**“轻量级标记语言”**。笔记、文章、技术评审文档、业务逻辑文档等等，我都想要使用Markdown去记录。几次寻觅，我找到了两款能够大部分符合我的需求的Markdown编辑器：**Typora**和**马克飞象**。

目前我是两款编辑器混合时候，当编写的Markdown文档需要和印象笔记对接的时候，则使用马克飞象；至于其他用途的文档就使用Typora。则两款编辑器都**近乎完美但是却又不能达到完美**。我写文档的时候经常需要截图，然后从剪贴板从直接黏贴放进文档，则两款编辑器虽然都能满足这种操作，但是其实现原理不过是**将截图存放在本机电脑上**，所以，一旦文档中有了截图，将Markdown文档的迁移到别的电脑上展示的成本就大大增加（图片也要一并复制过去）。

![][0]

_这是Typora对图片的解决方案_![][1]

_这是马克飞象中对图片的解决方案_这两款编辑器对图片处理的方法简直是丧尽天良，也是我在使用过程中唯一觉得不爽的一点。辛苦搜寻之下，终于让我找到了一种解决方案：**PicGo+GitHub图床**

> 注：实际上，Mac OS 上的Typora编辑器已经支持将本地图片或者截图先上传到服务器生成访问链接后，在存放到Markdown文档中，简单点说，Mac OS上的Typora是完美的（😭无奈我是Windows用户）

# [PicGo介绍][2]

这是一款图片上传的工具，目前支持微博图床，七牛图床，腾讯云，又拍云，GitHub等图床，未来将支持更多图床。

所以解决问题的思路就是，将本地的文件，或者剪切板上面的截图发送图床，然后生成在线图片的链接，这样就可以让Markdown文档飞起来了，走到哪就可以用到哪😊。

![][3]

_Pic Go支持的图床_在众多的图床中，我选择的GitHub图床，其它类型的图床如果你们有兴趣的话可以试一下。

# 创建自己的GitHub图床

## 1. 创建GitHub图床之前，需要注册/登陆GitHub账号

> 申请GitHub账号很简单，我就不演示了

## 2. 创建Repository

![][4]

_点击"New repository"按钮_![][5]

_最后1234步骤执行_* > 我已经建立过一个同名的repository的，所以第一步会显示红色
* > 第三步，为repository初始化一个README.md文件可以根据需求选择，非必选

## 3.生成一个Token用于操作GitHub repository

![][6]

_回到主页，点击"Settings"按钮_![][7]

_进入页面后，点击"Developer settings"按钮_![][8]

_点击"Personal access tokens"按钮_![][9]

_创建新的Token_![][10]

_填写描述，选择"repo",然后点击"Generate token"按钮_> 注：创建成功后，会生成一串token，这串token之后不会再显示，所以第一次看到的时候，就要好好保存

# 配置PicGo

## 1. 下载运行PicGo

![][11]

_下载zip包后，解压，运行可执行文件_## 2. 配置图床

![][12]

_如图配置_* > 设定仓库名的时候，是按照“账户名/仓库名的格式填写”
* > 分支名统一填写“master”
* > 将之前的Token黏贴在这里
* > 存储的路径可以按照我这样子写，就会在repository下创建一个“img”文件夹
* > 自定义域名的作用是，在上传图片后成功后，PicGo会将“自定义域名+上传的图片名”生成的访问链接，放到剪切板上> https://raw.githubusercontent.com/用户名/RepositoryName/分支名，> ，自定义域名需要按照这样去填写

## 3.快捷键及相关配置

![][13]

_可以按照这样配置_> 注：可以将快捷键设置为> ctrl+shift+c# 总结

将上面的步骤都设置好之后，就可以让自己的Markdown文档飞起来了，每次截图之后，都可以按一下ctrl+shift+c，这样就会将剪切板上面的截图转化为在线网络图片链接，简直就是爽的不要不要的！！

[0]: http://img.bai-long.cn/img/20190916191041.png
[1]: http://img.bai-long.cn/img/20190916191105.png
[2]: https://link.juejin.im?target=https%3A%2F%2Fgithub.com%2FMolunerfinn%2FPicGo
[3]: http://img.bai-long.cn/img/20190916191305.png
[4]: http://img.bai-long.cn/img/20190916191344.png
[5]: http://img.bai-long.cn/img/20190916191404.png
[6]: http://img.bai-long.cn/img/20190916191435.png
[7]: http://img.bai-long.cn/img/20190916191503.png
[8]: http://img.bai-long.cn/img/20190916191524.png
[9]: http://img.bai-long.cn/img/20190916191537.png
[10]: http://img.bai-long.cn/img/20190916191619.png
[11]: http://img.bai-long.cn/img/20190916191632.png
[12]: http://img.bai-long.cn/img/20190916191725.png
[13]: http://img.bai-long.cn/img/20190916191703.png
