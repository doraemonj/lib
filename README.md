## 私人图书馆完全技术手册

>   Are you ready to take control of your library?

-   藏书千本：深藏北冰洋的Github硬盘，帮你把维护费用彻底降为0
-   独立生存：没人能干涉，保管好密码，你的图书馆完全属于你
-   全文搜索：请点击右上角放大镜当场体验高速性能
-   分类标签：轻松给藏书分类、打标签，极简定位关联内容
-   随时翻译：任何一本外文书都能迅速翻译成中文版：
-   扩展性强：笔记区、留言区、内外兼修的无限存储，尽在你掌握



windows 电脑测试



作者：卷笔刀下的机器猫
链接：https://www.zhihu.com/question/21168463/answer/2681319452
来源：知乎
著作权归作者所有。商业转载请联系作者获得授权，非商业转载请注明出处。

## 一、准备工作：Git、Hugo和Github

### 1、Git首先是安装Git

Git是一个创世纪般的管理工具，可以让杂乱的代码瞬间清爽，让你像坐时光机一样穿梭于以前和现在的版本之间。你本该昨天就学Git，今天学也不迟，最好别拖到明天，因为后天你会后悔。Mac一般默认安装Git，如果你是Windows或Linux用户，可搜索下载，安装需配置环境变量。检查是否安装Git，Mac系统按Command+空格打开Spotlight，在搜索框输入terminal，点击终端打开命令行：



输入：git version



显示git version 2.32.1的字样，则已安装，忽略版本号差异。2、安装HugoHugo本是博客管理工具，它的特点是速读快，扩展性好，像是给私人图书馆量身定制一样。如果你的Mac系统已经安装好homebrew，那么一行代码搞定安装：brew install hugo
检查Hugo安装情况，直接输入：hugo version
如果出现hugo版本号，则安装成功：



如果独立安装homebrew或Hugo遇到普通中文使用者都会遇到的困难，那么可以前往某宝寻求小店支持，大约15-20元的样子就能搞定。3、注册GitHub账号，申请Github Pages打开http://github.com，点击右上角Sign up，



输入邮箱、密码和用户名



Github会向你的邮箱发送8位验证码，输入：



通过验证，显示欢迎页面：



Github里有个概念——『仓库』（repository）音标：[rɪ’pɔzitəri]。那里是你堆放代码的地方。你可以在Github里建几百几千个代码仓库，但只能有一个用来当图书馆的仓库，就是Github Pages。点击 Create repository，新建仓库：



在仓库名Repository name一栏下，填写你的用户名，后面加.github.io：



勾选 『Add a README file』选项，点击『新建仓库』，如果创建成功，会出现以下页面：



检查新建的仓库，打开网址：http://doraemonfile.github.io  ，显示：



虽然白底黑字并没有沾上多少喜气，但你自己的图书馆已悄然降临人世间，因为你自己的Github Pages已经注册成功。



### 二、用Hugo创建私人图书馆

私人图书馆本质上是一个博客，但超越普通博客功能之上。虽然有很多其他的备选框架，比如Jekyll、Hexo和Wordpress等，但经过两三年摸索，Hugo是毫无疑问的第一名，首要因素是快。Hugo的快是出了名的，不管是100本书还是1000本书，Hugo都能像1本书那样超快编译完成。而其他架构都会因为书变多而拉跨速度。我们已经装好了Hugo，接下来从最简单、但却最核心的功能开始：存放与显示文本1、下载图书馆直接在命令行输入：git clone https://github.com/doraemonj/my_library.git





如果你想一步到位，直接获得只属于你的电子图书馆，请联系微信：oftendie，10分钟帮你搞定，并且可以持续更新。

