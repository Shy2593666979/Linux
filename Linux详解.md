# Linux详解

## 一、安装Linux操作系统

### VMware介绍

 VMware（虚拟机）是指通过软件模拟的具有完整硬件系统功能的、运行在一个完全隔离环境中的完整计算机系统，通过它可在一台电脑上同时运行更多的Microsoft Windows、Linux、Mac OS X、DOS系统。

### 安装虚拟机VMware

软件网站：https://pan.baidu.com/s/1zcOp06HX4OxPdsCCGkHbXQ

密码：7777

1.鼠标右击【VMware16.0】选择【解压到VMware16.0】。

![图片](https://img-blog.csdnimg.cn/img_convert/ceb24fcff5facf3ac9328de93b01fb2e.png)

2.打开解压后的文件夹，鼠标右击【VMware-workstation-full-16.0.0-16894299】选择【以管理员身份运行】。

![图片](https://img-blog.csdnimg.cn/img_convert/713aa04e161e41eb6ff6ad3767339532.png)

3.点击【下一步】。

![图片](https://img-blog.csdnimg.cn/img_convert/392e0375f559525f5c751b4c11c0c6cc.png)

4.勾选【我接受许可协议中的条款】，点击【下一步】。

![图片](https://img-blog.csdnimg.cn/img_convert/d39be2ec9a9e2f0ca4dd5ad5e98ca6a8.png)

5.点击【更改…】。

![图片](https://img-blog.csdnimg.cn/img_convert/ff3251b6d852b9675b370ab3772ffbd6.png)

6.修改“文件夹名称”路径地址中的C可更改安装位置（我这里将C改为D表示安装在D盘），点击【确定】。

![图片](https://img-blog.csdnimg.cn/img_convert/ddd5aff6046e4c9f1215f7a197395d52.png)

7.点击【下一步】。

![图片](https://img-blog.csdnimg.cn/img_convert/2cf2deb5cba83df4e88c6fa2d61d7992.png)

8.取消勾选【启动时检查……】和【加入VMware……】，点击【下一步】。

![图片](https://img-blog.csdnimg.cn/img_convert/82c3b17479b48973e8257b8a7059ef8b.png)

9.点击【下一步】。

![图片](https://img-blog.csdnimg.cn/img_convert/0cf3ff5a3903ffb6b1f6491cfd0e2b1d.png)

10.点击【安装】。

![图片](https://img-blog.csdnimg.cn/img_convert/4b42791a98b912e7d2635187dcbe44b4.png)

11.软件安装中……

![图片](https://img-blog.csdnimg.cn/img_convert/f65aa3d4855de365dce72728c7fa553f.png)

12.点击【许可证】。

![图片](https://img-blog.csdnimg.cn/img_convert/8248aa93ba2684d77ca096ea1e43b101.png)

13.输入许可证密钥【ZF3R0-FHED2-M80TY-8QYGC-NPKYF】（以下可任意输入一组），点击【输入】。

```c++
ZF3R0-FHED2-M80TY-8QYGC-NPKYF

YF390-0HF8P-M81RQ-2DXQE-M2UT6

ZF71R-DMX85-08DQY-8YMNC-PPHV8
```

![图片](https://img-blog.csdnimg.cn/img_convert/6b4b0a3d802b5fd218a50feb8b821404.png)

14.安装完成，点击【完成】。

![图片](https://img-blog.csdnimg.cn/img_convert/eea69cc8c5b8265f58908f80b62e9b49.png)

15.双击桌面【VMware Workstation Pro】图标启动软件。

![图片](https://img-blog.csdnimg.cn/img_convert/9caf8a461f71cf38126848b25ef227cb.png)

16.安装成功。

![图片](https://img-blog.csdnimg.cn/img_convert/eaa72575d019862c9b1cf5de36004511.png)

### 下载centos 7系统

下载网址：[centos-7-isos-x86_64安装包下载_开源镜像站-阿里云 (aliyun.com)](http://mirrors.aliyun.com/centos/7/isos/x86_64/)

### 安装centos 7系统

成功引导系统后，会出现下面的界面
**界面说明：**

- Install CentOS Linux 7 	安装CentOS 7

- Test this media & install CentOS Linux 7 	测试安装文件并安装CentOS7

- Troubleshooting 	修复故障![CentOS 7系统安装配置图文详解](https://img-blog.csdnimg.cn/img_convert/23d82bb0ebf0d7b68d1f7c31fd02bb39.gif)

1.这里选择Install CentOS Linux7，安装CentOS 7，回车，进入下面的界面
![CentOS 7系统安装配置图文详解](https://img-blog.csdnimg.cn/img_convert/13839d36de95e086e064848e499f2d41.gif)

2.回车，进入下面的界面
![CentOS 7系统安装配置图文详解](https://img-blog.csdnimg.cn/img_convert/515e99715562e499650a7ae9f2f8b6ab.gif)

3.等待到Checking：100%，进入下面的界面
![CentOS 7系统安装配置图文详解](https://img-blog.csdnimg.cn/img_convert/e3d208ab45baf9605ca1234c17ac7bc7.gif)

4.语言选择界面，正式生产服务器建议安装英文版本。Continue继续
![CentOS 7系统安装配置图文详解](https://img-blog.csdnimg.cn/img_convert/ebfffa7ab983fe5d1b8b6581dc60eed6.gif)

5.选择DATE&TIME，设置日期和时间，然后选择Done
![CentOS 7系统安装配置图文详解](https://img-blog.csdnimg.cn/img_convert/2d5d70f566b28e212f9c28b2fa50e4c0.gif)

6.再次选择INSTALLATION DESTINATION，进入磁盘分区界面（我选择自动配置分区， 默认即可），然后选择Done
界面说明：

- Automatically configure partitioning 	自动配置分区
- I will configure partitioning  	自己配置分区
- I would like to make additional space available 	提供额外的空间

![CentOS 7系统安装配置图文详解](https://img-blog.csdnimg.cn/img_convert/4421ff30e26005ebdb7a5f81f64e1993.gif)

7.其他设置默认即可
![CentOS 7系统安装配置图文详解](https://img-blog.csdnimg.cn/img_convert/f5090f8b03c55819386fd32514e0953f.gif)

8.选择Begin Installation开始安装，进入下面的界面
![CentOS 7系统安装配置图文详解](https://img-blog.csdnimg.cn/img_convert/3c264a3f2d491fd29140970d7da7501f.gif)

9.选择ROOT PASSWORD，设置root密码，然后选择Done
![CentOS 7系统安装配置图文详解](https://img-blog.csdnimg.cn/img_convert/35b3a082e317b9d8df3a031607d3bd3a.gif)

10.选择USER CREATION，创建用户并设置密码，然后选择Done
![CentOS 7系统安装配置图文详解](https://img-blog.csdnimg.cn/img_convert/c1464ded5ce5c2a5a67a43e0cba2142d.gif)

11.安装完成之后，会进入下面的界面.（可能需要10分钟作用），选择Reboot
![CentOS 7系统安装配置图文详解](https://img-blog.csdnimg.cn/img_convert/57779b9496808aeb66f832c61b8a5833.gif)

12.重启之后，进入如下界面
![CentOS 7系统安装配置图文详解](https://img-blog.csdnimg.cn/img_convert/2b569ac440ca7a1ae0ca59d72a6d60e8.gif)

13.输入之前设置的用户名和密码进入下面的界面
![CentOS 7系统安装配置图文详解](https://img-blog.csdnimg.cn/img_convert/7f6c67e167b55db9123473dd6b488ad3.gif)

到此CentOS系统安装完成



## 二、Linux基础命令

### Linux的目录结构

- Linux的目录结构是一个树型结构

- Windows 系统可以拥有多个盘符, 如 C盘、D盘、E盘

- Linux没有盘符这个概念, 只有一个根目录 /, 所有文件都在它下面

![请添加图片描述](https://img-blog.csdnimg.cn/cdf7f009327641e8976acbf2dc95a249.png)


- 在Linux系统中，路径之间的层级关系，使用：/ 来表示

- 在Windows系统中，路径之间的层级关系，使用： \ 来表示

### Linux命令入门

无论是什么命令，用于什么用途，在Linux中，命令有其通用的格式：

```shell
command  [-options]  [parameter]
```

- command： 命令本身

- -options：[可选，非必填]命令的一些选项，可以通过选项控制命令的行为细节

- parameter：[可选，非必填]命令的参数，多数用于命令的指向目标等

[ ] 表示可选的意思

如下语法，ls命令是可以使用选项的

```shell
ls [-a -l -h] [Linux路径]
```

- -a选项，表示：all的意思，即列出全部文件（包含隐藏的文件/文件夹）

- -l选项，表示：以列表（竖向排列）的形式展示内容，并展示更多信息

- -h 表示以易于阅读的形式，列出文件大小，如K、M、G

- -h选项必须要搭配 -l 一起使用

![在这里插入图片描述](https://img-blog.csdnimg.cn/efa4e638eb5b4d79a8e87bd9beb84489.png)


### 目录切换相关命令 cd、pwd

**cd 命令**

当Linux终端（命令行）打开的时候，会默认以用户的HOME目录作为当前的工作目录

我们可以通过cd命令，更改当前所在的工作目录。

cd命令来自英文：Change Directory

```shell
cd [Linux路径]
```

- cd命令无需选项，只有参数，表示要切换到哪个目录下

- cd命令直接执行，不写参数，表示回到用户的HOME目录

**pwd命令**

我们可以通过pwd命令，来查看当前所在的工作目录。

pwd命令来自：Print Work Directory

语法：

- pwd命令，无选项，无参数，直接输入pwd即可

![\[外链图片转存失败,源站可能有防盗链机制,建议将图片保存下来直接上传(img-SjpwFQAf-1692935083103)(C:\Users\枯木逢春i\AppData\Roaming\Typora\typora-user-images\image-20230824115200545.png)\]](https://img-blog.csdnimg.cn/f4e66d8ac17d43f2bf4c91a2f90cd34a.png)


### 相对路径、绝对路径和特殊路径符

通过pwd得知当前所在是HOME目录：/home/user

现在想要通过cd命令，切换工作目录到Desktop文件夹中去。

那么，cd命令的参数（Linux路径）如何写呢？

```shell
- cd /home/user/Desktop

- cd Desktop
```

上述两种写法，都可以正确的切换目录到指定的Desktop中。

**绝对路径**：以根目录为起点，描述路径的一种写法，路径描述以/开头

**相对路径**：以当前目录为起点，描述路径的一种写法，路径描述无需以/开头

**特殊路径符：**

- . 表示当前目录，比如 cd ./Desktop 表示切换到当前目录下的Desktop目录内，和cd Desktop效果一致

- .. 表示上一级目录，比如：cd ..  即可切换到上一级目录，cd ../.. 切换到上二级的目录

- ~ 表示HOME目录，比如：cd ~  即可切换到HOME目录或cd ~/Desktop，切换到HOME内的Desktop目录

### 掌握通过mkdir命令创建文件夹

通过mkdir命令可以创建新的目录（文件夹）

mkdir来自英文：Make Directory

```shell
mkdir [-p] [Linux路径]
```

- 参数必填，表示Linux路径，即要创建的文件夹的路径，相对路径或绝对路径均可

- -p选项可选，表示自动创建不存在的父目录，适用于创建连续多层级的目录

如果想要一次性创建多个层级的目录不加 -p 会报错，因为lession和class目录不存在

可以通过-p选项，将一整个链条都创建完成。

![在这里插入图片描述](https://img-blog.csdnimg.cn/ca72d7e9c8e34121b063b462034011f6.png)


**ps：**创建文件夹需要修改权限，请确保操作均在HOME目录内，不要在HOME外操作涉及到权限问题，HOME外无法成功。

### 文件操作命令touch、cat、more

可以通过touch命令创建文件

语法： 

```shell
touch [Linux路径]
```

- touch命令无选项，参数必填，表示要创建的文件路径，相对、绝对、特殊路径符均可以使用

![在这里插入图片描述](https://img-blog.csdnimg.cn/5bd2d0834a1345a0b26ccabc5374876c.png)




准备好文件内容后，可以通过cat查看内容。

语法：

```shell
cat [Linux路径]
```

- cat同样没有选项，只有必填参数，参数表示：被查看的文件路径，相对、绝对、特殊路径符都可以使用
![在这里插入图片描述](https://img-blog.csdnimg.cn/4d2fae315f204639aa757d32c2e4cbc9.png)



more命令同样可以查看文件内容，同cat不同的是：

- cat是直接将内容全部显示出来

- more支持翻页，如果文件内容过多，可以一页页的展示

语法：

```shell
more [Linux路径]
```

- 同样没有选项，只有必填参数，参数表示：被查看的文件路径，相对、绝对、特殊路径符都可以使用

### 文件操作命令cp、mv、rm

**cp命令复制文件文件夹**

cp命令可以用于复制文件\文件夹，cp命令来自英文单词：copy

语法：

```shell
cp [-r] 参数1 参数2
```

- -r选项，可选，用于复制文件夹使用，表示递归

- 参数1，Linux路径，表示被复制的文件或文件夹

- 参数2，Linux路径，表示要复制去的地方

![在这里插入图片描述](https://img-blog.csdnimg.cn/8ef03a0e082043a1986e0b2ae93e642c.png)


**mv移动文件或文件夹**

mv命令可以用于移动文件\文件夹，mv命令来自英文单词：move

语法：

```shell
mv 参数1 参数2
```

- 参数1，Linux路径，表示被移动的文件或文件夹

- 参数2，Linux路径，表示要移动去的地方，如果目标不存在，则进行改名，确保目标存在

**rm删除文件夹、文件 **

rm命令可用于删除文件、文件夹

rm命令来自英文单词：remove

语法：

```shell
rm 参数1 参数2 参数3 ...
```

- 同cp命令一样，-r选项用于删除文件夹

- -f表示force，强制删除（不会弹出提示确认信息）

- 普通用户删除内容不会弹出提示，只有root管理员用户删除内容会有提示

- 所以一般普通用户用不到-f选项

参数1、参数2、......、参数N 表示要删除的文件或文件夹路径，按照空格隔开

![在这里插入图片描述](https://img-blog.csdnimg.cn/a517ae81ef0b4d06b3e0404ed05841ba.png)


rm命令支持通配符 *，用来做模糊匹配

- 符号* 表示通配符，即匹配任意内容（包含空），示例：

- test*，表示匹配任何以test开头的内容

- *test，表示匹配任何以test结尾的内容

- *test*，表示匹配任何包含test的内容

### 查找命令which、find

我们在前面学习的Linux命令，其实它们的本体就是一个个的二进制可执行程序。

和Windows系统中的.exe文件，是一个意思。



我们可以通过which命令，查看所使用的一系列命令的程序文件存放在哪里

语法：

```shell
which Linux命令
```
![在这里插入图片描述](https://img-blog.csdnimg.cn/6519480019a24adca178f826a6c120ac.png)



在Linux系统中，我们可以通过find命令去搜索指定的文件。

语法：

```shell
find 起始路径 -name "文件名"
```

被查找文件名，支持使用通配符 * 来做模糊查询。

- 符号* 表示通配符，即匹配任意内容（包含空），示例：

- test*，表示匹配任何以test开头的内容

- *test，表示匹配任何以test结尾的内容

- *test*，表示匹配任何包含test的内容

基于通配符的含义，可以结合find命令做文件的模糊查询。

![在这里插入图片描述](https://img-blog.csdnimg.cn/513f8328d8c443c0bbf283a3303390b6.png)


**find命令** **-** **按文件大小查找文件**

语法

```shell
find 起始路径 -size +|-n[KMG]
```

- +、- 表示大于和小于

- n表示大小数字

- kMG表示大小单位，k(小写字母)表示kb，M表示MB，G表示GB

示例：

- 查找小于10KB的文件： find / -size -10k

- 查找大于100MB的文件：find / -size +100M

- 查找大于1GB的文件：find / -size +1G

### grep、wc和管道符

**grep命令**

可以通过grep命令，从文件中通过关键字过滤文件行。

语法：

```shell
grep [-n] 关键字 文件路径
```



•选项-n，可选，表示在结果中显示匹配的行的行号。

•参数，关键字，必填，表示过滤的关键字，带有空格或其它特殊符号，建议使用””将关键字包围起来

•参数，文件路径，必填，表示要过滤内容的文件路径，可作为内容输入端口

**wc命令做数量统计**

可以通过wc命令统计文件的行数、单词数量等

语法：

```shell
wc [-c -m -l -w ] 文件路径
```

- 选项，-c，统计bytes数量

- 选项，-m，统计字符数量

- 选项，-l，统计行数

- 选项，-w，统计单词数量

- 参数，文件路径，被统计的文件，可作为内容输入端口

![在这里插入图片描述](https://img-blog.csdnimg.cn/22c3538d39bd45c0bff3409430e54008.png)


### echo、tail和重定向符

**echo命令**

可以使用echo命令在命令行内输出指定内容

语法：

```shell
echo 输出内容
```

- 无需选项，只有一个参数，表示要输出的内容，复杂内容可以用””包围

- 带有空格或\等特殊符号，建议使用双引号包围

如下命令：echo pwd

本意是想，输出当前的工作路径，但是pwd被作为普通字符输出了。

我们可以通过将命令用反引号（通常也称之为飘号）`` 包围的内容，会被作为命令执行，而非普通字符

重定向符：>和>>

- 第一个将左侧命令的结果，覆盖写入到符号右侧指定的文件中

- 第二个将左侧命令的结果，追加写入到符号右侧指定的文件中

```shell
echo “Hello Linux” > a.txt 
```

就是把 Hello  Linux 输入到 a.txt 中

```shell 
echo “Hello world” > a.txt
```

再次执行，覆盖新内容

```shell
echo “Hello Code” >> a.txt
```

再次执行，使用>>追加新内容

**tail 命令**

使用tail命令，可以查看文件尾部内容，跟踪文件的最新更改，语法如下：

```shell
tail [-f -num] Linux路径
```

- 参数，Linux路径，表示被跟踪的文件路径
- 选项，-f，表示持续跟踪
- 选项, -num，表示，查看尾部多少行，不填默认10行

**举例：**

```shell
查看/var/log/vmware-network.log文件的尾部10行：tail /var/log/vmware-network.log
```

```shell
查看/var/log/vmware-network.log文件的尾部3行：tail -3 /var/log/vmware-network.log
```

### Vim编辑器

**vi\vim编辑器介绍**

vi\vim是visual interface的简称, 是Linux中最经典的文本编辑器

同图形化界面中的 文本编辑器一样，vi是命令行下对文本文件进行编辑的绝佳选择。

vim 是 vi 的加强版本，兼容 vi 的所有指令，不仅能编辑文本，而且还具有 shell 程序编辑的功能，可以不同颜色的字体来辨别语法的正确性，极大方便了程序的设计和编辑性。

**vi\vim编辑器的三种工作模式**

1、命令模式（Command mode）

​		命令模式下，所敲的按键编辑器都理解为命令，以命令驱动执行不同的功能。

​		此模型下，不能自由进行文本编辑。

2、输入模式（Insert mode）

​		也就是所谓的编辑模式、插入模式。

​		此模式下，可以对文件内容进行自由编辑。

3、底线命令模式（Last line mode）

 	  以：开始，通常用于文件的保存、退出。

如果需要通过vi/vim编辑器编辑文件，请通过如下命令：

```shell
vi 文件路径
vim 文件路径
```

vim兼容全部的vi功能，后续全部使用vim命令

- 如果文件路径表示的文件不存在，那么此命令会用于编辑新文件

- 如果文件路径表示的文件存在，那么此命令用于编辑已有文件

**命令模式快捷键**

![在这里插入图片描述](https://img-blog.csdnimg.cn/48680ec57ffa45afbe8729f9bbf510fb.png)

![在这里插入图片描述](https://img-blog.csdnimg.cn/371ba3c1bc08482191f7a60a00a2e124.png)


**底线命令模式**

编辑模式没有什么特殊的，进入编辑模式后，任何快捷键都没有作用，就是正常输入文本而已。

唯一大家需要记住的，就是：通过esc，可以退回到命令模式中即可。

在命令模式内，输入: ，即可进入底线命令模式，支持如下命令：

![在这里插入图片描述](https://img-blog.csdnimg.cn/442fa3fe0f2545d0ac1c7667815b2b18.png)


## 三、Linux用户和权限

### 认知root用户

无论是Windows、MacOS、Linux均采用多用户的管理模式进行权限管理。

- 在Linux系统中，拥有最大权限的账户名为：root（超级管理员）

- 而在前期，我们一直使用的账户是普通的用户：user

**su和exit命令**

在前面，我们接触过su命令切换到root账户。

su命令就是用于账户切换的系统命令，其来源英文单词：Switch User

语法：

```shell
su [-] 用户名
```

- -符号是可选的，表示是否在切换用户后加载环境变量（后续讲解），建议带上
- 参数：用户名，表示要切换的用户，用户名也可以省略，省略表示切换到root
- 切换用户后，可以通过exit命令退回上一个用户，也可以使用快捷键：ctrl + d
- 使用普通用户，切换到其它用户需要输入密码，如切换到root用户
- 使用root用户切换到其它用户，无需密码，可以直接切换

**sudo命令**

在我们得知root密码的时候，可以通过su命令切换到root得到最大权限。

但是我们不建议长期使用root用户，避免带来系统损坏



我们可以使用sudo命令，为普通的命令授权，临时以root身份执行。

语法：

```shell
sudo 其他命令
```

- 在其它命令之前，带上sudo，即可为这一条命令临时赋予root授权

- 但是并不是所有的用户，都有权利使用sudo，我们需要为普通用户配置sudo认证

**为普通用户配置sudo认证**

- 切换到root用户，执行visudo命令，会自动通过vi编辑器打开：/etc/sudoers

- 在文件的最后添加：

```shell
user ALL=(ALL)  NOPASSWD: ALL
```

- 其中最后的NOPASSWD:ALL 表示使用sudo命令，无需输入密码

- 最后通过 wq 保存

### 用户、用户组管理

**用户、用户组**

Linux系统中可以：

- 配置多个用户

- 配置多个用户组

- 用户可以加入多个用户组中

Linux中关于权限的管控级别有2个级别，分别是：

- 针对用户的权限控制

- 针对用户组的权限控制

比如，针对某文件，可以控制用户的权限，也可以控制用户组的权限。



**用户组管理**

我们需要学习在Linux中进行用户、用户组管理的基础命令，为后面学习权限控制打下基础。

以下命令需root用户执行

- 创建用户组

groupadd 用户组名

- 删除用户组

groupdel 用户组名

为后续演示，我们创建一个case用户组：groupadd case



**用户管理**

以下命令需root用户执行

- 创建用户

```shell
useradd [-g -d] 用户名
```

- 选项：-g指定用户的组，不指定-g，会创建同名组并自动加入，指定-g需要组已经存在，如已存在同名组，必须使用-g
- 选项：-d指定用户HOME路径，不指定，HOME目录默认在：/home/用户名
- 删除用户

```shell
userdel [-r] 用户名
```

- 选项：-r，删除用户的HOME目录，不使用-r，删除用户时，HOME目录保留
- 查看用户所属组a

```shell
id [用户名]
```

- 参数：用户名，被查看的用户，如果不提供则查看自身

- 修改用户所属组

usermod -aG  用户组 用户名，将指定用户加入指定用户组

**getent**

使用getent命令，可以查看当前系统中有哪些用户

语法：

```shell
 getent passwd
```

使用getent命令，同样可以查看当前系统中有哪些用户组

语法：

```shell
getent group
```

### 查看权限控制
![在这里插入图片描述](https://img-blog.csdnimg.cn/f6d7731ac8ba41a0bf03a4bad9b005e2.png)

红色圈出来的表示文件、文件夹的权限控制信息

![在这里插入图片描述](https://img-blog.csdnimg.cn/55a79155a41f4978a259f9cf0b506bba.png)

- r表示读权限
- w表示写权限
- x表示执行权限

针对文件、文件夹的不同，rwx的含义有细微差别

- r，针对文件可以查看文件内容

​	  -针对文件夹，可以查看文件夹内容，如ls命令

- w，针对文件表示可以修改此文件

​      - 针对文件夹，可以在文件夹内：创建、删除、改名等操作

- x，针对文件表示可以将文件作为程序执行

​      - 针对文件夹，表示可以更改工作目录到此文件夹，即cd进入

### 修改权限控制 - chmod

**chmod命令**

我们可以使用chmod命令，修改文件、文件夹的权限信息。

注意，只有文件、文件夹的所属用户或root用户可以修改。

语法：

```shell
chmod [-R] 权限 文件或文件夹
```

- 选项：-R，对文件夹内的全部内容应用同样的操作

**权限的数字序号**

权限可以用3位数字来代表，第一位数字表示用户权限，第二位表示用户组权限，第三位表示其它用户权限。

数字的细节如下：r记为4，w记为2，x记为1，可以有：

- 0：无任何权限， 即 ---
- 1：仅有x权限， 即 --x
- 2：仅有w权限 即 -w-
- 3：有w和x权限 即 -wx
- 4：仅有r权限 即 r--
- 5：有r和x权限 即 r-x
- 6：有r和w权限 即 rw-
- 7：有全部权限 即 rwx

751表示： rwx(7) r-x(5) --x(1)

### 修改权限控制 - chown

使用chown命令，可以修改文件、文件夹的所属用户和用户组

普通用户无法修改所属为其它用户或组，所以此命令只适用于root用户执行

语法：

```shell
chown [-R] [用户][:][用户组] 文件或文件夹
```

- 选项，-R，同chmod，对文件夹内全部内容应用相同规则
- 选项，用户，修改所属用户
- 选项，用户组，修改所属用户组
- : 用于分隔用户和用户组

## 四、Linux实用操作

### 各类小技巧（快捷键）

1. ctrl + c 强制停止

2. ctrl + d 退出登出

3. history 查看历史命令

4. !命令前缀，自动匹配上一个命令

5. ctrl + r，搜索历史命令

6. ctrl + a | e，光标移动到命令开始或结束

7. ctrl + ← | →，左右跳单词

8. ctrl + l 或 clear命令 清屏

### 软件安装

**Linux系统的应用商店**

操作系统安装软件有许多种方式，一般分为：

- 下载安装包自行安装
- 如win系统使用exe文件、msi文件等
- 如mac系统使用dmg文件、pkg文件等
- 系统的应用商店内安装
- 如win系统有Microsoft Store商店
- 如mac系统有AppStore商店



Linux系统同样支持这两种方式，我们首先，先来学习使用：Linux命令行内的”应用商店”，yum命令安装软件



**yum命令**

yum：RPM包软件管理器，用于自动化安装配置Linux软件，并可以自动解决依赖问题。

语法：

```shell
yum [-y] [install | remove | search] 软件名称
```



- 选项：-y，自动确认，无需手动确认安装或卸载过程

- install：安装

- remove：卸载

- search：搜索



**ps:**

- yum命令需要root权限哦，可以su切换到root，或使用sudo提权。

- yum命令需要联网

**apt命令（在Ubuntu系统）** 

前面学习的各类Linux命令，都是通用的。 但是软件安装，CentOS系统和Ubuntu是使用不同的包管理器。

CentOS使用yum管理器，Ubuntu使用apt管理器

通过前面学习的WSL环境，我们可以得到Ubuntu运行环境。

语法：

```shell
apt [-y] [install | remove | search] 软件名称
```

用法和yum一致，同样需要root权限

- apt install wget，安装wget

- apt remove wget，移除wget

- apt search wget，搜索wget

### systemctl命令

Linux系统很多软件（内置或第三方）均支持使用systemctl命令控制：启动、停止、开机自启

能够被systemctl管理的软件，一般也称之为：服务

语法：

```shell
systemctl start | stop | status | enable | disable 服务名
```

```shell
start 启动
stop 关闭
status 查看状态
enable 开启开机自启
disable 关闭开机自启
```

系统内置的服务比较多，比如：

- NetworkManager，主网络服务

- network，副网络服务

- firewalld，防火墙服务

- sshd，ssh服务（FinalShell远程登录Linux使用的就是这个服务）

### 软连接

在系统中创建软链接，可以将文件、文件夹链接到其它位置。

类似Windows系统中的《快捷方式》

语法：

```shell
ln -s 参数1 参数2
```



-  -s选项，创建软连接

-  参数1：被链接的文件或文件夹

-  参数2：要链接去的目的地

实例：

```shell
ln -s /etc/yum.conf ~/yum.conf

ln -s /etc/yum ~/yum
```

### 日期、时区

**date命令**

通过date命令可以在命令行中查看系统的时间

语法：

```she
date [-d] [+格式化字符串]
```

- -d 按照给定的字符串显示日期，一般用于日期计算

- 格式化字符串：通过特定的字符串标记，来控制显示的日期格式
  - %Y  年
  - %y  年份后两位数字 (00..99)
  - %m  月份 (01..12)
  - %d  日 (01..31)
  - %H小时(00..23)
  - %M 分钟 (00..59)
  - %S  秒 (00..60)
  - %s  自 1970-01-01 00:00:00 UTC到现在的秒数

**修改Linux时区**

使用root权限，执行如下命令，修改时区为东八区时区

```shell
rm -f /etc/localtime
sudo ln -s /usr/share/zoneinfo/Asia/Shanghai /etc/localtime
```

将系统自带的localtime文件删除，并将/usr/share/zoneinfo/Asia/Shanghai文件链接为localtime文件即可

### IP地址、主机名

**IP地址**

每一台联网的电脑都会有一个地址，用于和其它计算机进行通讯

IP地址主要有2个版本，V4版本和V6版本（V6很少用，课程暂不涉及）

IPv4版本的地址格式是：a.b.c.d，其中abcd表示0~255的数字，如192.168.88.101就是一个标准的IP地址



可以通过命令：ifconfig，查看本机的ip地址，如无法使用ifconfig命令，可以安装：yum -y install net-tools

![在这里插入图片描述](https://img-blog.csdnimg.cn/64b1535372c0406aac8f093515beb121.png)



**主机名**

在Linux系统中输入hostname 查看主机名

可以使用命令：hostnamectl set-hostname 主机名，修改主机名（需root）

**域名解析**

![在这里插入图片描述](https://img-blog.csdnimg.cn/900ee3f52d2f47a18b5a4ed361d01fc7.png)


### 网络传输

**ping命令**

可以通过ping命令，检查指定的网络服务器是否是可联通状态

语法：

```shell
ping [-c num] ip或主机名
```

- 选项：-c，检查的次数，不使用-c选项，将无限次数持续检查

- 参数：ip或主机名，被检查的服务器的ip地址或主机名地址

![在这里插入图片描述](https://img-blog.csdnimg.cn/d67262f4cbff4b339ef0b91b24286226.png)


**wget命令**

wget是非交互式的文件下载器，可以在命令行内下载网络文件

语法：

```shell
wget [-b] url
```

- 选项：-b，可选，后台下载，会将日志写入到当前工作目录的wget-log文件

- 参数：url，下载链接

**curl命令**

curl可以发送http网络请求，可用于：下载文件、获取信息等

语法：

```shell
curl [-O] url
```

- 选项：-O，用于下载文件，当url是下载链接时，可以使用此选项保存文件

- 参数：url，要发起请求的网络地址

**端口**

1. 什么是端口？

端口是指计算机和外部交互的出入口，可以分为物理端口和虚拟端口

- 物理端口：USB、HDMI、DP、VGA、RJ45等

- 虚拟端口：操作系统和外部交互的出入口

IP只能确定计算机，通过端口才能锁定要交互的程序

2. 端口的划分

- 公认端口：1~1023，用于系统内置或常用知名软件绑定使用
- 注册端口：1024~49151，用于松散绑定使用（用户自定义）
- 动态端口：49152~65535，用于临时使用（多用于出口）

3. 查看端口占用

- nmap IP地址，查看指定IP的对外暴露端口

- netstat -anp | grep 端口号，查看本机指定端口号的占用情况

### 压缩、解压

**压缩格式**

- zip格式：Linux、Windows、MacOS，常用

- 7zip：Windows系统常用

- rar：Windows系统常用

- tar：Linux、MacOS常用

- gzip：Linux、MacOS常用

在Windows系统中常用的软件如：winrar、bandizip等软件，都支持各类常见的压缩格式，这里不多做讨论。

我们现在要学习，如何在Linux系统中操作：tar、gzip、zip这三种压缩格式

完成文件的压缩、解压操作。

**tar命令**

Linux和Mac系统常用有2种压缩格式，后缀名分别是：

- .tar，称之为tarball，归档文件，即简单的将文件组装到一个.tar的文件内，并没有太多文件体积的减少，仅仅是简单的封装

- .gz，也常见为.tar.gz，gzip格式压缩文件，即使用gzip压缩算法将文件压缩到一个文件内，可以极大的减少压缩后的体积

针对这两种格式，使用tar命令均可以进行压缩和解压缩的操作

语法：

```shell
tar [-c -v -x -f -z -C] 参数1 参数2 ... 参数N
```



- -c，创建压缩文件，用于压缩模式
- -v，显示压缩、解压过程，用于查看进度
- -x，解压模式
- -f，要创建的文件，或要解压的文件，-f选项必须在所有选项中位置处于最后一个
- -z，gzip模式，不使用-z就是普通的tarball格式
- -C，选择解压的目的地，用于解压模式

**tar的常用组合为：**

```shell
tar -cvf test.tar 1.txt 2.txt 3.txt
```

将1.txt 2.txt 3.txt 压缩到test.tar文件内

```shell
tar -zcvf test.tar.gz 1.txt 2.txt 3.txt
```

将1.txt 2.txt 3.txt 压缩到test.tar.gz文件内，使用gzip模式



**注意：**

•-z选项如果使用的话，一般处于选项位第一个

•-f选项，必须在选项位最后一个



**tar解压组合**

```shell
tar -xvf test.tar
```

解压test.tar，将文件解压至当前目录

```shell
tar -xvf test.tar -C /home/user
```

解压test.tar，将文件解压至指定目录（/home/user）

```shell
tar -zxvf test.tar.gz -C /home/user
```

以Gzip模式解压test.tar.gz，将文件解压至指定目录（/home/user）



**注意：**

•-f选项，必须在选项组合体的最后一位

•-z选项，建议在开头位置

•-C选项单独使用，和解压所需的其它参数分开



**zip命令压缩文件**

可以使用zip命令，压缩文件为zip压缩包

语法：

```shell
zip [-r] 参数1 参数2 ...
```

- -r，被压缩的包含文件夹的时候，需要使用-r选项，和rm、cp等命令的-r效果一致



演示：
```shell
zip test.zip a.txt b.txt c.txt
```
将a.txt b.txt c.txt 压缩到test.zip文件内
```shell
zip -r test.zip test case a.txt
```
将test、case两个文件夹和a.txt文件，压缩到test.zip文件内

**unzip** **命令解压文件**

使用unzip命令，可以方便的解压zip压缩包

语法：

```shell
unzip [-d] 参数
```

- -d，指定要解压去的位置，同tar的-C选项

- 参数，被解压的zip压缩包文件

演示：

```shell
unzip test.zip
```
将test.zip解压到当前目录
```shell
unzip test.zip -d /home/user
```
将test.zip解压到指定文件夹内（/home/user）
