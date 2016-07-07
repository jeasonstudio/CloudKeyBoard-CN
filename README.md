# **基于云端同步的中文键盘项目计划书**

###  Tags：CloudKeyBoard-CN
###  Date：2016年 5月

![LOGO](https://raw.githubusercontent.com/jeasonstudio/CloudKeyBoard-CN/8e5389de483e8c77cbd4f7e4543fee9ddf5f05a0/Images/logo.png)

>学校名称：北京科技大学             
学院名称：计算机与通信工程学院  
专  业 ：计算机科学与技术          
成员姓名：赵吉彤、贾凡茗、王志陶 
队长学号：41524122               
指导教师：班晓娟                 


## **项目的简要介绍**

>对现有键盘进行优化改良，简化键盘使用，便于中文打字，支持个性化配置及云端同步，通过生产推广该键盘，令用户拥有更加流畅舒适的键盘体验，引领键盘交互新潮流。

## **项目的内容**

### 1、立项依据：

>最初，打字机的键盘是按照字母顺序排列的，但如果打字速度过快，某些键的组合很容易出现卡键问题。于是克里斯托夫·拉森·寿斯（Christopher Latham Sholes）发明了QWERTY键盘布局，他将最常用的几个字母安置在相反方向，最大限度放慢敲键速度以避免键盘卡键。寿斯在1868年申请专利，1873年使用此布局的第一台商用打字机成功投放市场。这就是为什么有今天键盘的排列方式。 
>但具有讽刺意味的是，这种129年前形成的、以放慢敲键速度为目的的键盘排列方式却延续至今。
>1986年布鲁斯·伯里文爵士曾在《奇妙的书写机器》一文中表示：“QWERTY的安排方式非常没效率。”比如：大多数打字员惯用右手，但使用QWERTY，左手却负担了57%的工作。两小指及左无名指是最没力气的指头，却要频频使用它们。排在中列的字母，其使用率仅占整个打字工作的30%左右，因此，为了打一个字，时常要上上下下移动指头。
>1930年奥格斯特·多冉柯(August Dvorak)发明了一种更优越的DUORAK键盘系统，将9个最常用的字母放在键盘中列。这种设计使打字者手指不离键就能打至少3000多个字。而QWERTY只能做到50个字。DUORAK是通过减少手指的运动量来降低工作强度、提高工作效率的。使用DUORAK，打字者的手指平均每日运动1英里，而QWERTY则是12到20英里。二战期间，奥格斯特·多冉柯曾集合14位海军打字员练习DUORAK键盘，1个月后，他们的速度惊人地提高了68%。DUORAK键盘让右手负担56%的工作；最有力的手指工作量最大；70%的打字工作是在中间一列进行而不必移动手指。但这始终是面向英文打字的键盘，而且当时正逢二次大战，作战物资缺乏，这种新键盘还没问市就停产了。


### 2、项目意义：

>这是一款面向中文打字的具有极强个性化的云键盘系统，他可以通过完善现有的键盘分布、使用我们推荐的中文输入键盘分布或是根据个人需求定制自己的专属键盘，再通过互联网与远程服务器关联，通过键盘旁加装的指纹（人脸）识别技术，快速的将任何一台新型智能键盘终端，打造成自己熟悉的键盘，随时随地提高自己的打字速度和对键盘的熟悉程度，最终实现打字键盘的个人习惯云端存储。

### 3、项目的内容及目标：

>项目内容：完成又键盘及树莓派及其他插件组成的各个键盘终端，完成云端建设，通过网络实现在各个终端完成个人习惯的同步。
>项目目标：对现有键盘进行优化改良，简化键盘使用，便于中文打字，支持个性化配置及云端同步，通过生产推广该键盘，令用户拥有更加流畅舒适的键盘体验，引领键盘交互新潮流。

### 4、项目可行性分析：

>⑴基于云端同步的中文键盘用到了单片机技术、Python 语言、键盘构造技术、服务器数据库搭建等技术，实施生产概念产品甚至量产都十分可行。
>⑵新型键盘领域创意或者产品较少，“QWERTY”键盘不合理，却根深蒂固，市场在这方面有改革创新的需求，有广泛的发展前景。

### 5、数据可行性：

![Dates](https://raw.githubusercontent.com/jeasonstudio/CloudKeyBoard-CN/8e5389de483e8c77cbd4f7e4543fee9ddf5f05a0/Images/02.png)

>以上是大量数据统计结果。下面是根据数据初步确定的键盘格局。

![practice](https://raw.githubusercontent.com/jeasonstudio/CloudKeyBoard-CN/8e5389de483e8c77cbd4f7e4543fee9ddf5f05a0/Images/05.png)

## **市场和销售安排**

### 1、市场的基本情况：

 - 该产品主要用于个人对键盘交互以及打字体验的提升。
 - 键盘市场被现有不合理键盘垄断，有很大改革的空间。

### 2、产品的客户情况，销售渠道的安排：

 - 客户情况:面向个人、面向打字较多的个体或组织。
 - 销售渠道:线上和实体店销售。
 
## **其他**

### 1.投资预算

>3000元以内试产几款概念样机。
宣传及推广费用2000+。

### 2.产品零售价

>云端同步功能中文键盘键盘单价估计为55$（360￥）。
>简易版中文键盘售价为23$（150￥）。

# 汉字爬虫(Chinese-Spider)

目录：../Chinese-Spider

##使用说明

1. 在src/CnkiSpider.py设置检索条件

2. 执行src/CnkiSpider.py抓取数据

3. 抓取数据存储在/data目录下，文件名格式为"data-keyword-年月日时分秒.txt.txt"，如"data-新媒体-20131128224556.txt"

4. 每个数据文件的第一行为字段名称

5. 每次运行都根据当前时间生成新的数据文件

6. 如果抓取过程中断，可以在src/CnkiSpider.py中设置startPage为中断时的页码，并重新运行src/CnkiSpider.py从中断的页面继续抓取，最后将各个数据文件合并

7. 生成的文本文件直接修改后缀名为.csv然后用LibreOffice打开并在LibreOffice中设置字段分隔符为src/CnkiSpider.py中变量fieldsSep设置的字符串

8. Windows下打开Excel 2013,然后【打开】->【浏览】->选择文件（文件名后下拉框选择“文本文件”），出现文本导入向导，设置“文件原始格式”为Unicode（UTF-8)，下一步，设置“分隔符号”

9. 由若要使用文本编辑器打开数据文件，建议使用Notepad++打开。Windows自带的记事本打开大文件会卡死。Notepad++可以自动识别编码格式，防止乱码。

10. 如果数据文件中从某部分开始大量出现关键词字段和分类号字段为空的情况，则将src/CnkiSpider.py中restEvery变量调小，restPeriod变量调大后重试。

## windows下和linux下使用需要修改的地方

CnkiSpider.py        print "----CONTENT:获取第" + str(article["order"]) + "篇文章"

ContentSpider.py     s = s.replace("【分类号】".decode("utf8"), "")
