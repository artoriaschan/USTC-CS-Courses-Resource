
# 中国科学技术大学课程资源
[![Stars](https://img.shields.io/github/stars/mbinary/USTC-CS-Courses-Resource.svg?label=Stars&style=social)](https://github.com/mbinary/USTC-CS-Courses-Resource/stargazers)
[![Forks](https://img.shields.io/github/forks/mbinary/USTC-CS-Courses-Resource.svg?label=Fork&style=social)](https://github.com/mbinary/USTC-CS-Courses-Resource/network/members)
[![repo-size](https://img.shields.io/github/repo-size/mbinary/USTC-CS-Courses-Resource.svg)]()
[![Contributors](https://img.shields.io/github/contributors/mbinary/USTC-CS-Courses-Resource.svg)](https://github.com/mbinary/USTC-CS-Courses-Resource/graphs/contributors)
[![License](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-nc-sa/4.0/)

>本仓库收录中国科学技术大学众多课程资源，包括电子版教材、参考书、讲义、试卷、学习心得、习题解答等。以计算机学院课程为主，也包含公选课、自由选修等其他课程。


# 目录
<!-- vim-markdown-toc GFM -->

* [版权说明](#版权说明)
* [反馈方式](#反馈方式)
* [资料下载](#资料下载)
* [课程结构](#课程结构)
* [课程目录](#课程目录)
* [贡献投稿](#贡献投稿)
    * [投稿方式](#投稿方式)
        * [帮忙上传](#帮忙上传)
        * [网页操作](#网页操作)
        * [用命令行](#用命令行)
    * [投稿建议](#投稿建议)

<!-- vim-markdown-toc -->
# 版权说明
本仓库分享资料遵守其创作者之规定。

对无特别声明的资料，谨以[知识共享署名 - 非商业性使用 - 相同方式共享 4.0 国际许可协议](http://creativecommons.org/licenses/by-nc-sa/4.0/) 授权。![](https://i.creativecommons.org/l/by-nc-sa/4.0/80x15.png)

抵制盗版，人人有责。我们正在征询任课教师许可分享讲义、试卷、作业、实验等内容，仅分享合法资料。

请贡献者遵守版权规定，尊重原创劳动，注明资料来源；

请创作者及公众监督，如有资料违反许可协议，请告知我们改正错误。

# 反馈方式
- [issue](https://github.com/mbinary/USTC-CS-Courses-Resource/issues/new)
- <a href="mailto:&#122;huheqin1@gmail.com?subject=%E5%8F%8D%E9%A6%88%E4%B8%8E%E5%BB%BA%E8%AE%AE">email</a>
- [QQ](http://wpa.qq.com/msgrd?v=3&uin=414313516&site=qq&menu=yes)

# 资料下载
## FTP
1. FTP/FTPS:
   - 地址：ftp.ustclug.org；
   - 路径：/ebook/USTC-CS-Courses-Resource；
   - 用户名：ftp；
   - 密码：ftp；
2. SFTP (Secure File Transfer Protocol):
   - 地址：ftp.ustclug.org；
   - 路径：/ebook/USTC-CS-Courses-Resource；
   - 用户名：ftp；
   - 密码：ftp；
3. AFP (Apple Filing Protocol)
   - 地址：afp://ftp.ustclug.org/；
   - 路径：/ebook/USTC-CS-Courses-Resource；
   - Connect As Guest

感谢 @USTC-LUG, @[zzh1996](https://github.com/zzh1996), @[volltin](https://github.com/volltin) 

## HTTPS
- [github 网页](#课程目录)
- [脚本生成的网页](https://mbinary.xyz/ustc-cs/)
- [gitzip 下载工具](https://kinolien.github.io/gitzip)

FTP 快速，可以下载整个目录，是最好的选择，gitzip 可以打包下载（方法是输入 github repo 中的文件夹地址）, 脚本生成的网页浏览起来更快，会有更多信息，比如文件大小等

# 课程结构
每门课程大致结构如下，有些栏目可能没有，也可以自己添加认为合理的栏目

* 教材，答案在课程目录下
* 参考书，参考资料在 reference 下
* 复习试卷，习题课，作业解答 在 review 下
* 建立文件夹 homework-teacher1, homework-teacher2 ..., lab-teacher1, 每个文件夹中如果有不同年份的，就再建立不同年份的文件夹
* 课程主页及其他链接资源记在 README.md 中
* slides: 主要是 ppt 文件类型，**将所有 slides** 打包成 zip, 放在 课程目录下（若有多个老师，则在课程目录建立 slides-teacherName1.zip, slides-teacherName2.zip...）
* students（同学们上传的自己的一些资料，作品，每个同学新建一个目录）


如 编译原理和技术 课程
```
├ lab- 张昱
│   └ 2017
├ lab- 李诚
│   ├ lab-1
│   ├ lab-2
│   ├ lab-3
│   ├ lab-4
│   ├ pre
│   ├ README.md
│   └ Server_Guide.pdf
├ lab- 郑启龙
│   ├ lab1-declarationParser
│   └ lab2-pl0
├ README.md
├ reference
│   ├ Programming_Language_Pragmatics(b-ok.xyz).pdf
│   ├ The garbage collection handbook  the art of automatic memory management.PDF
│   ├ 垃圾回收的算法与实现 --- 文字版.pdf
│   └ 编译原理术语中英文对照表.pdf
├ review
│   ├ 2010 作业答案.pdf
│   ├ 2014 期末试卷.pdf
│   ├ 2017 习题课 - 张昱.pdf
│   ├ 2018-final-review.pdf
│   ├ 2018 习题课 - 李诚.pdf
│   ├ 2018 习题课 - 郑启龙.pdf
│   ├ 2018 期中考试试题与参考答案.pdf
│   └ ex_on_PL0.pdf
├ slides- 张昱.zip
├ slides- 李诚.zip
└ slides- 郑启龙.zip
```
# 课程目录
**根据拼音字母排序**, 可以通过在此页面搜索课程名快速定位。

* [.](.)
    * [经管类](./经管类)
        * [宏观经济学](./经管类/宏观经济学)
        * [会计学原理](./经管类/会计学原理)
        * [生产与运作管理](./经管类/生产与运作管理)
        * [市场营销](./经管类/市场营销)
        * [微观经济学](./经管类/微观经济学)
    * [计算机与信息类](./计算机与信息类)
        * [编译原理和技术](./计算机与信息类/编译原理和技术)
        * [并行计算](./计算机与信息类/并行计算)
        * [操作系统原理与设计](./计算机与信息类/操作系统原理与设计)
        * [c程序设计](./计算机与信息类/c程序设计)
        * [程序设计语言基础(英)](./计算机与信息类/程序设计语言基础(英))
        * [计算机体系结构](./计算机与信息类/计算机体系结构)
        * [计算机网络](./计算机与信息类/计算机网络)
        * [计算机系统概论(ICS)](./计算机与信息类/计算机系统概论(ICS))
        * [计算机系统详解(csapp)](./计算机与信息类/计算机系统详解(csapp))
        * [计算机组成原理](./计算机与信息类/计算机组成原理)
        * [类型系统](./计算机与信息类/类型系统)
        * [密码学](./计算机与信息类/密码学)
        * [模拟与数字电路](./计算机与信息类/模拟与数字电路)
        * [脑与认知科学导论](./计算机与信息类/脑与认知科学导论)
        * [python](./计算机与信息类/python)
        * [人工智能导论](./计算机与信息类/人工智能导论)
        * [人工智能基础](./计算机与信息类/人工智能基础)
        * [软件工程](./计算机与信息类/软件工程)
        * [scheme](./计算机与信息类/scheme)
        * [数电实验](./计算机与信息类/数电实验)
        * [数据结构](./计算机与信息类/数据结构)
        * [数据科学导论](./计算机与信息类/数据科学导论)
        * [数据库系统及应用](./计算机与信息类/数据库系统及应用)
        * [数理逻辑](./计算机与信息类/数理逻辑)
        * [算法基础](./计算机与信息类/算法基础)
        * [图论](./计算机与信息类/图论)
        * [Web-信息处理与应用](./计算机与信息类/Web-信息处理与应用)
        * [微机原理与系统](./计算机与信息类/微机原理与系统)
        * [物联网导论](./计算机与信息类/物联网导论)
    * [其他](./其他)
    * [人文社科类](./人文社科类)
        * [交响乐赏析](./人文社科类/交响乐赏析)
        * [马克思主义基本原理概论](./人文社科类/马克思主义基本原理概论)
        * [重要思想概论](./人文社科类/重要思想概论)
    * [数学类](./数学类)
        * [多变量微积分](./数学类/多变量微积分)
        * [概率论与数理统计B](./数学类/概率论与数理统计B)
        * [计算方法](./数学类/计算方法)
        * [数理方程](./数学类/数理方程)
        * [随机过程](./数学类/随机过程)
        * [线性代数B1](./数学类/线性代数B1)
        * [运筹学基础](./数学类/运筹学基础)
    * [utils](./utils)
    * [物理类](./物理类)
        * [大学物理实验](./物理类/大学物理实验)
        * [电磁学](./物理类/电磁学)
        * [光学与原子物理](./物理类/光学与原子物理)

# 贡献投稿
欢迎大家的参与与贡献，投稿的时候注意[版权说明](#版权说明)

## 投稿方式

### 帮忙上传
可以发给我或者其他同学帮忙上传，或者提 issue

### 网页操作
* 用网页或者[桌面版](https://desktop.github.com/) 直接操作，fork and pull request,
   操作方式可以参考 [这里](https://blog.csdn.net/qq_29277155/article/details/51048990) 和[这里](https://blog.csdn.net/zhangw0_0/article/details/50667891) ,[介绍 pr 操作](https://blog.csdn.net/huutu/article/details/51018317)

### 用命令行
对于用命令行的同学，提醒一下这个仓库很大（2019-1-25 时已有 7G 左右）
所以如果直接 clone 很慢。
可以使用 sparse-checkout, 只下载你指定的目录

首先用网页操作，创建你想要的目录（已有的可以直接用）, 如在公选课目录下创建`人工智障`,
然后在 cli 执行
```shell
mkdir ustc-courses  #文件夹名可以自己取
cd ustc-courses
git init
git remote add -f origin  git@github.com:mbinary/USTC-CS-Courses-Resource.git
git config core.sparsecheckout true
echo "计算机与信息类/软件工程"  >> .git/info/sparse-checkout  #这里工作目录就是在那个 repo 主页下

#如果还有其他目录，都像上面一样加入即可，如 `echo  "计算机与信息类/图论/slides" >> .git/info/sparse-checkout`
#只需记住的是 加入的目录应该在远程仓库存在，否则报错“error: Sparse checkout leaves no entry on the working directory”

git pull origin master
git remote add upstream git@github.com:mbinary/USTC-CS-Courses-Resource.git
```
建议：如果没有较大的改动，或者在改动之前，可以删除掉以前 fork 的仓库 重新 fork

更新内容后
```shell
git fetch upstream/master
git merge upstream/master
```

## 投稿建议
* github 上不能直接上传大于 100mb 的文件。对于超过 100 mb 的文件，可以存在网盘，然后在 README 文件中贴上链接
* 文件内容的改动会使 git 重新上传, 在没有必要的情况下, 不要对二进制文件做任何更改.
