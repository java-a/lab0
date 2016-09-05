# lab0
熟悉课程相关的网站，并完成软件安装与注册。




##访问课程ftp
1.打开“我的电脑”，在地址栏输入软件学院ftp地址。

> ftp://10.132.141.33

![address](https://cloud.githubusercontent.com/assets/9759891/18254814/4f15a89a-73d4-11e6-8b12-757da48e1f6c.png)

2.在弹出的对话框中输入用户名和密码。

>用户名：ss  
>密码：ss

![login](https://cloud.githubusercontent.com/assets/9759891/18254756/b3930f0c-73d3-11e6-8ef0-aa95857e54ec.png)

3.依次进入：class -> 16 -> 161 程序设计（戴开宇），即可进入课程目录。

##下载并安装Chrome浏览器
1. 在课程目录的material文件夹下复制![chrome_package](https://cloud.githubusercontent.com/assets/9759891/18254827/75e3206a-73d4-11e6-859c-5d90e1b539ff.png)安装包到本地
2. 解压文件，并运行
3. 安装成功

## GitHub

### GitHub是什么

当我们在编写程序时，我们往往和其他人一起协作，共同完成一个软件的开发。对于大型软件来说，团队中成员之间的协作及代码的版本管理变得尤为重要。

GitHub就是这样一个提供了版本控制的代码托管网站。也就是说，你可以将一个项目的代码储存在GitHub的一个仓库中，并允许别人与你共同开发这个项目。除此之外，它也提供了一些方便社会化软件开发的功能，包括允许用户追踪其他用户、组织、软件库的动态，对软件代码的改动和bug提出评论等。GitHub也提供了图表功能，用于显示开发者们怎样在代码库上工作以及软件的开发活跃程度。

截止到2015年，GitHub已经有超过九百万注册用户和2110万代码库。**事实上已经成为了世界上最大的代码存放网站和开源社区。**

### 我们使用GitHub做什么

在期末Project中，我们或许会试着使用GitHub来管理一个项目的开发。但这已经远远超出了我们当前的要求。**目前，我们使用GitHub来查看课程文档和讨论。**

我们将这门课程托管在GitHub上，所有课程材料都可以在[课程主页](https://github.com/orgs/java-a)中找到。具体地来说：

- 在课程的[大纲仓库](https://github.com/java-a/syllabus)中，你可以找到一些课程的推荐阅读。

- 在课程的[大纲仓库的讨论区](https://github.com/java-a/syllabus/issues)中，你可以提出自己的问题，或是回答其他同学的问题。助教看到问题之后将会第一时间回复，同时也欢迎同学们在上面回复其他同学的问题。最终成绩中的平时分与讨论相关。

- 每个布置的Lab（上机作业）和Project都会拥有一个单独的项目仓库。以这个Lab为例，它的主页为：

  > https://github.com/java-a/lab0

  你可以在线查看文档，或是将这个仓库下载到本地后查看。

### 如何使用GitHub

1. 注册GitHub账号。选择你喜欢的用户名、学号邮箱及密码，点击 `Sign up for GitHub` 前往注册。
   ![image](https://cloud.githubusercontent.com/assets/7262715/18254555/665afc4c-73d1-11e6-8db0-be555d8e75e2.png)

2. 前往课程主页：https://github.com/java-a。


1. 熟悉[如何在讨论区中发布新的帖子？](https://github.com/java-a/syllabus/issues/1)及[如何回复一个帖子？](https://github.com/java-a/syllabus/issues/2)。



## 开发工具

对编程人员来说，使用稳定、强大、方便的开发工具可以有效提升编程的效率和正确性。在本课程中，我们一开始使用简洁明了的文本编辑器Atom。当大家熟悉Java编程后，我们将使用IntelliJ IDEA，一个专业的集成开发环境(IDE, Integrated Development Environment) 。

### Atom

Atom是一个简洁易用的现代文本编辑器，具有很强的可扩展功能。

相比IntelliJ IDEA，Atom缺少了很多开发功能的支持，比如代码自动补全、语法报错、断点调试等。但是Atom适用于几乎所有的编程语言，无论是Java， C，C++，还是Python，JavaScript，Ruby等编程语言，都可以很方便地使用Atom进行编程。同时，Atom拥有强大的社区插件(Plugin)支持，能为Atom附加各种不同的功能。拥有各种插件支持的Atom有时甚至比集成开发环境(IDE)更加好用。

#### 安装Atom：

1. 在资源管理器中打开：

   [ftp://10.132.141.33/classes/16/161%20%B3%CC%D0%F2%C9%E8%BC%C6A%20%A3%A8%B4%F7%BF%AA%D3%EE%A3%A9/Materials/](ftp://10.132.141.33/classes/16/161%20%B3%CC%D0%F2%C9%E8%BC%C6A%20%A3%A8%B4%F7%BF%AA%D3%EE%A3%A9/Materials/)

   用户名：ss，密码：ss。

2. 复制atom-windows.zip到电脑桌面。

3. 右键atom-windows.zip，解压至当前目录。

4. 打开解压后的文件夹Atom，打开文件夹内的atom.exe启动atom。

5. 完成，如图：

   ![Alt text](https://cloud.githubusercontent.com/assets/6532225/18254055/7a525a74-73cc-11e6-92ff-9162da69ff38.png)



在下个Lab中，我们将学习如何使用Atom编辑Java程序，并运行第一个程序"Hello world!"。

Atom官方地址：https://atom.io/

### IntelliJ IDEA

IntelliJ IDEA是目前最先进的Java集成开发环境，提供了非常强大的开发功能支持，可以大幅提升代码开发效率，并更好地进行项目管理和维护。关于如何安装使用IntelliJ，我们会在大约一个月后学习。

IntelliJ IDEA将会是大家大学四年的主力开发工具，大部分的代码都会使用IntelliJ开发。

除了本课程外，同学们还将在这些课程中使用IntelliJ的开发：

- 大一下学期的`Web应用基础`
- 大二上学期的`算法与数据结构`
- 大三的`计算机图形学`，`高级Web`
- 选修课，如`智能移动平台应用开发`等

IntelliJ IDEA官方地址：https://www.jetbrains.com/idea/

