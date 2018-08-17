# 工大ACM15天训练计划（工程实践方向）  

## 15天计划池
+ 概论
+ Ubuntu安装，基础命令熟悉
+ Github账号创建
+ 后端语言基础入门
+ 前端入门
+ SQL使用入门
+ 找到自己发展方向和兴趣点
+ 做自己喜欢的项目（没有就增删改查和带登录的博客系统）
+ 面向企业技术栈搭建
+ 数据结构不可少

## 2018.08.15  
### 1.查看[ToACM](https://github.com/SUTFutureCoder/ToSUTACM/)导论，认清现状和未来公认发展方向  
坑都被学长们踩过了，就像期末已经画好重点，多少你们的前辈因为没有意识到这些关键点虚度大学三年，让自己去了自己不满意的地方或是直接考研碰大运。   
里面写的不保证适用性，请培养自己的独立思考能力。毕业后也不要被其他人、郭嘉、舆论牵着走。   
对于互联网企业，只跟着老师上课的乖宝宝，简历注定被扔进垃圾桶。  

### 2.先选择一门喜欢的后端语言
从现在起禁止使用VC++，工作时候任何情况下都用不到的技术，在学校也不要花时间和技能点放到这上面，请把时间花在刀刃上。  
推荐选择Java技术栈，Java这几年招聘市场仍然非常广，各种中间件和解决方案非常多。  
PHP技术栈入门快，适合快速成型的项目，但招聘市场趋于萎缩。  
C、C++技术栈不推荐，招聘要求过高，非985、211、大硕或水平高请勿硬钢。但C、C++算法训练很有用。  
Python、GO技术栈虽然不推荐，但你可以业余研究一下，写工具、爬虫有用。GO比较适合分布式多线程。  
如果走前端路线，JS则是必修课。后端也可以使用Node实现。   
**注意，任何语言和技术都有它适合使用的场景。只ALL IN除了Java、PHP外一门语言比较危险，因为各位无论如何都去找工作吧。所以无论现在和未来，都不要把自己局限为某语言开发工程师。**    
这回让各位自行选择喜欢的后端语言，我和板砖个人推荐Java。因为我是PHP、Go、Python、JS技术栈，所以Java如果有疑问请联系板砖  
**禁止把时间浪费在比较语言和技术优劣，只有是否适合某个场景。把时间花在上手实践上**  

### 3.我今天做什么呢
#### 1.找到喜欢后端语言后，那就准备快速上手吧
如何劝退新手？看巨厚的书、老师上课枯燥教学。所以能快速上手然后实践试错是王道。  

#### 2.那我去哪里学？
[菜鸟教程](http://www.runoob.com/)
推荐入门的第一步  
[菜鸟教程-java](http://www.runoob.com/java/java-tutorial.html)  
[菜鸟教程-php](http://www.runoob.com/php/php-tutorial.html)  
[菜鸟教程-python](http://www.runoob.com/python/python-tutorial.html)  
[菜鸟教程-go](http://www.runoob.com/go/go-tutorial.html)

[w3c](http://www.w3school.com.cn/)
w3c比较适合PHP和前端技术栈  
[w3c-php](http://www.w3school.com.cn/php/index.asp)  

想要通过视频手把手教
[java1234学习路线图](http://www.java1234.com/javaxuexiluxiantu.html)  

书籍推荐  
SAMS出的××入门经典是我大部分技术入门第一本书
包括前后端语言、正则表达式。但SQL之类的可以直接w3c解决。  
[java入门经典](https://item.jd.com/11761109.html)  
[php入门经典](https://item.jd.com/25424540924.html)  
当然也可以找电子书，原则上支持正版  

#### 3.晚上回复进度
不要求一天全学会，至少基础部分能过一遍。  
语言学习要持续整个技术生涯，今天只是个开头。  

### 4.明后天计划准备
1. 下载VirtualBox
2. 下载Ubuntu镜像
3. 下载Git工具

## 2018.08.16
### 1.Github账号创建
Github是未来你的第0号简历，越早创建、把练习和个人开发项目放到上面越好。  
一般面试官如果看到你的简历上附有Github链接，则会点进去看看你的绿点（推代码情况）和项目情况。记住，潸然泪下的万字求职信不如一行高质量代码。而最直观展示你学习、潜力、探索、实践成果，就是Github。  
#### 1.需要我做什么？
1. 访问[github](http://github.com/)，创建一个账号。  
2. 下载github客户端，搜素安装方法  
3. 按照文档，创建rsa_key并添加到github上[创建rsakey](https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/),[添加key](https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/)  
4. github上[新建一个库](https://github.com/new)，名字随意。推荐叫practice  

下面针对使用命令行界面同学，如果使用图形化界面，请自行搜索图形化github使用。  

1. 使用```git clone```，将库克隆拉到本地  
2. 在本地新的库随意创建一个文件  
3. 使用```git add -A```,```git commit -m '本次推送内容'```,```git push```三个命令，将文件推到github上面。 

无论图形化还是命令行方法，都需要掌握以下命令，是面试重点。  
学习```git add```,```git commit```,```git push```,```git pull```,```git branch```,```git checkout```,```git log```,```git reset```含义及使用   

#### 2.群作业回复已创建的github账号。

#### 3.持续跟着08.15继续入门语言
并且把跟着教程学习代码放到github上，以后所有练习和个人项目代码都需要放上面。  

### 2.继续学习```8.15```选择的语言
创建Github相关比较简单，如果已完成```1```的内容，剩下的时间请将今天的练习代码push到github上。  

### 3.附加任务 安装Ubuntu18.04 desktop
如果你使用的是MACOS，那可以忽略掉这一部分。  
为什么要用Linux/Unix而不用Windows呢？因为所有的大型互联网公司服务器都运行在非windows操作系统上，日常维护、查线上问题都需要熟练掌握linux，没有掌握Linux命令直接过不了第一道简历筛选关。  
可以自行搜索virtualbox安装ubuntu方法，虽然可能虚拟机运行比较慢，但一上来就让你装双系统或直接放弃windows全部使用Linux作为日常操作系统不是很友好。所以今天先安装上Ubutnu，可以自己随便操作操作，适应一下新操作系统。最好能运行terminal终端试一试能否用命令行控制你的Linux。  

## 2018.08.17
### 1.Linux简单熟悉
需要了解```/```、```/home```,```/bin```等各个目录的含义。 
 
### 2.Linux命令熟悉
Linux命令是面试重点，而且工作后几乎每天都会使用。  
假如线上出现了线上事故，老大们都在看着，如何快速响应、定位、修复，也是晋升的必备能力。  

#### 1.基础命令
需要了解以下命令的作用和使用方法  
```ls```,```pwd```,```cd```,```mkdir```,```touch```,```mv```,```rm```,```cp```,```sudo```,```ps```,```top```,```history```      

#### 2.工具使用
1. vim
因为线上服务器不会提供图形化编辑工具，所以一些工作会在vim中进行。对于一些高手来说，vim使用熟练了能够脱离鼠标，编码速度加倍。当然vim入门有一定曲线，需要背一些基础键位。    
需要了解vim的安装  
提示 ``sudo apt-get install vim``  
需要了解vim的基础使用  
[打怪升级入门指南](https://coolshell.cn/articles/5426.html)    
[cheatsheet键位图方便理解](https://raw.githubusercontent.com/Gtskk/vim-cheatsheet/master/img/vim.png)  

2. tar
压缩传文件必备，可以尝试自己打包和解包。  
压缩样例：``tar zcf test.tar.gz waimai_*``  
解压缩样例: ``tar zxvf test.tar.gz``   

3. ssh
连接服务器必备，未来如果有了自己的服务器，也可以使用ssh进行登录。目前可以先尝试自己连接自己。  
``ssh 127.0.0.1``  
有非常大概率会报错~那么如何解决呢？请自行搜索，并学习如何启动服务。  


### 3.需要我今天做什么？
1. 继续熟悉昨天和前天学习语言基础  
2. 入门Linux基础命令  
3. 尝试使用Linux工具，提交感受和收获到作业中  
4. 最后~执行命令``cowsay "我碉堡了Σ(゜゜)"``
5. 尝试安装mysql相关工具。（提前熟悉）  


