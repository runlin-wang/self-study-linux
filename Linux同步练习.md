高等教育自学考试

Linux系统及应用

课程代号（04948 ）

同步练习题


| 班级 |      |
| ---- | ---- |
| 学号 |      |
| 姓名 |      |


二O一六年一月


目录


[第一章 Linux系统概述	1](#第一章-Linux系统概述)

[第二章 Linux常用命令	3](#第二章-Linux常用命令)

[第三章 文本编辑	8](#第三章-文本编辑)

[第四章 Linux shell 程序设计	10](#第四章-Linux-shell-程序设计)

[第五章 Linux内核简介	15](#第五章-Linux内核简介)

[第六章 常用开发工具	16](#第六章-常用开发工具)

[第七章 Linux 环境编程](#第七章-Linux-环境编程)

[第八章 Linux系统管理	17](#第八章-Linux系统管理)

[第九章 网络应用及管理	22](#第九章-网络应用及管理)

[第十章 嵌入式操作系统简介](#第十章-嵌入式操作系统简介)



## 第一章 Linux系统概述

一、单项选择题

1. 最初开发了Linux系统的是（    ）

A．Andrew S. Tanwnbaum				Ｂ．Linus Torvalds

Ｃ．Ken Thompson 					D．Dennis Ritchie

2. linux操作系统内核创始人是（    ）

A．Bill Gates						B．Richard Stallman		

C．Linus Torvalds					D．Dennis Ritchie

3. linux操作系统下有很多应用软件，其中大部分软件包括linux本身属于（    ）

A.商业软件		B. 共享软件			C.自由软件			D.其他类型软件

4. Linux 核心的许可证是什么（   ）

A．NDA			B．GDP				C．GPL			D．GNU

5. 若要将鼠标从VM中释放出来，可按什么键来实现（    ）

A. Ctrl + Alt		B. Ctrl +Alt +Del		C. Ctrl +Alt +Enter		D Ctrl +Enter

6. GNU的含义是（    ）

A．GNU是UNIX	Ｂ．GNU不是UNIX Ｃ．UNIX工程		D．GNU工程

7. 下列不是Linux优点的是（    ）

A. 全32位操作系统 					B. 多任务的操作系统

C. 是一个多用户操作系统				D. 单线程

8. Linux下使用的图形用户界面是（    ）

A.X windows			B.KDE			C.X window			D.K桌面环境


二、填空题


三、判断改错题

9. Linus最早是由Linus Torvalds波兰人编写的。（   ）

10. 在安装好的Linux系统上，可以直接运行微软的IE5上网。（   ）

11. RedHat只支持图形安形方式。（   ）

12. Linux操作系统可以免费获得。（   ）

13. Linux的特点之一是它是一种开放、免费的操作系统。（   ）

14. linux的内核版本和发行版本号是一样的。（   ）

15. Linux是由法国人Linus开发出来的。（   ）

 

四、简答题

16. 简单说明Linux的发展优势与存在问题？

17. Linux之所以受到广大计算机爱好者的喜爱，其主要原因是什么？

 

五、操作题



## 第二章 Linux常用命令

一、单项选择题

18. 用 "rm -i",系统会提示什么来让你确认（    ）

A. 命令行的每个选项					B. 是否真的删除

C. 是否有写的权限 				D. 文件的位置

19. 显示文件的头部的命令是（    ）

A．fdisk			Ｂ．mount			Ｃ．head				D．man

20. 删除不需要的文件的命令是（    ）

A．mkdir			Ｂ．rm				Ｃ．mv				D．remove

21. 对名为fido的文件用chmod 551 fido 进行了修改，则它的许可权是（    ）

A -rwxr-xr-x		B -rwxr--r--			C -r--r--r--			D -r-xr-x--x

22. 用于文件系统直接修改文件权限管理命令为（    ）

A. chown			B. chgrp				C. chmod				D. umask

23. 若使pid进程无条件终止使用的命令是（    ）

A. kill -9			B. kill -15			C. killall -1			D. kill -3

24. rm命令表示什么（    ）

A移动文件命令	B文件复制命令		C文件删除命令		D文件内容统计命令

25. Linux文件权限一共10位长度，分成四段，第三段表示的内容是（    ）

A 文件类型 							B 文件所有者的权限 

C 文件所有者所在组的权限 			D 其他用户的权限

26. 删除当前目录abc以及下面的所有子目录和文件，并不要求提示任何确认信息的命令是（    ）

A．del abc*.*			Ｂ．rm –rf  abc	Ｃ．rmdir abc			D．rm –r abc .

27. linux中图象文件属于（    ）

A．文本文件 			Ｂ．连接文件 	Ｃ．特殊文件 		D．二进制文件

28. 在缺省情况下，使用ls -color命令显示当前目录下的所有文件时，对于可执行文件一般显示为（    ）

A．红				Ｂ．绿			Ｃ．黄				D．蓝

29. 确定myfile的文件类型的命令是什么（   ）

A. type myfile						B. type -q myfile	

C. file myfile						D.whatis myfile

30. 用来分离目录名和文件名的字符是什么（   ）

A. slash (/)							B. period (.)		

C. dash (-)							D. asterisk (*)

31. 你想显示文件"longfile"的最后10行，下面那个命令是正确的（   ）

A. tail logfile						B. head －10 longfile	

C. taid －d 10 longfile				D. head longfile

32. 假如你得到一个运行命令被拒绝的信息，你可以用哪个命令去修改它的权限使之可以正常运行（   ）

A. path=			B. chmod 		C. chgrp			D. chown

33. 下面哪个Linux命令可以一次显示一页内容？（    ）

A．pause				Ｂ．cat			Ｃ．more			D．grep

34. 怎样更改一个文件的权限设置？（    ）

A．attrib				B．chmod		C．change			D．file

35. 如果你的umask设置为022，缺省的，你创建的文件的权限为（    ）

A．----w--w-			B．-w--w----		C． r-xr-x---			D．rw-r--r--

36. linux中，显示当前登录用户详细信息的是（    ）

A．uname				Ｂ．who			Ｃ．who  ami		D．whose

37. 下面关于命令mv说法错误的是（    ）

A．mv命令可以重命名文件				B．mv命令可以移动文件

C．mv命令可以复制文件				D．mv命令可以删除文件

38. 在使用ln建立文件链接时，为了不分配新的i node，需要使用（    ）

A．普通链接		Ｂ．硬链接			Ｃ．软链接			D．特殊链接

39. grep -v,表示（    ）

A．只显示整行严格匹配的行			B．只显示匹配行的数量    

C．只显示不包含匹配串的行			D．指定检索使用的模式

40. 关于ls命令说法不正确的有（    ）

A．-a 可显示当前目录下的所有文件

B．与dir命令类似

C．-A 与 -a 功能相同，但显示的文件更多

D．-d  当遇到目录时列出目录本身而非目录内的文件

41. 如果忘记了ls命令的用法，可以采用哪个命令获得帮助（    ）

A. ？ls				B. help ls			C. man ls				D. get ls

42. 要给文件file1加上其他人可执行属性的命令是（    ）

A.chmod a+x file1						B.chown a+x file1	

C.chmod o+x file1						D.chown o+x file1

43. 拷贝mydir/myfile文件到dir2目录下，但是系统提示这个文件已经存在，下面那个命令是正确的（   ）

A. cp －w mydir/myfile dir2			B. cp -i mydir/myfile dir2		

C. cp mydir/myfile dir2				D. cp -v mydir/myfile dir2

44. 使用$cd ~命令后，会进入哪个目录（    ）

A. /					B. ~ 			C.用户的主目录		D. /tmp

45. 下面那个命令允许对文件重命名（   ）

A. rn				B. rname				C. replace		D. mv

46. 假如文件是按8进制来定义，下面那个值代表了读和写（   ）

A.2				B.6					C.4				D.1

47. pwd命令的功能是（   ）

A 设置用户的口令  

B 显示用户的口令 

C 相当于Windows命令行里输入CD命令

D 相当于在windows命令行里输入dir命令

48. 执行命令“chmod o+rw myfile”后，myfile文件的权限变化为（    ）

A.同组用户可读写myfile文件			B.其他用户可读写myfile文件 

C.所有用户都可读写myfile文件			D.文件所有者读写myfile文件 

49. 怎样新建一个新目录（    ）

A. touch hello	B. mkdir hello		C. rm hello			D. new hello 

50. Linux下的cp命令用于复制文件或目录，该命令是最重要的文件操作命令，其命令格式哪项是正确的（    ）

A． cp	[选项]	源文件	目标文件

B． cp	[选项]	目标目录  目标文件

C． cp	[选项]	目标文件  源文件

D． cp	[选项]	目标文件  目标目录  

51. cp命令常用选项中 哪个实现保持原先文件的所有者，组权限和时间标志（    ）

A -l				B –m				C  -p				D -k 

52. Linux有三个查看文件的命令，若希望在查看文件内容过程中可以用光标上下移动来查看文件内容，应使用（    ）

A cat				B more				C less				D menu

53. 对名为fido的文件用chmod 551 fido 进行了修改，则它的许可权是（    ）

A -rwxr-xr-x 							B -rwxr－－r－－ 

C -r－－r－－r－－ 					D -r-xr-x—x

54. 用ls –al 命令列出下面的文件列表，哪个文件是符号连接文件（   ）

A -rw-rw-rw- 2 hel-s users 56 Sep 09 11:05 hello 

B -rwxrwxrwx 2 hel-s users 56 Sep 09 11:05 goodbey 

C drwxr－－r－－ 1 hel users 1024 Sep 10 08:10 zhang 

D lrwxr－－r－－ 1 hel users 2024 Sep 12 08:12 cheng

55. 删除文件命令为（   ）

A mkdir			B rmdir				C mv 			D rm

56. 哪一个命令能用来查找在文件TESTFILE中只包含四个字符的行（   ）

A. grep '????' TESTFILE 			B. grep '....' TESTFILE

C. grep '^????$' TESTFILE				D. grep '^....$' TESTFILE

57. 按哪个键能中止当前运行的命令（   ）

A. Ctrl-D			B. Ctrl-C			C. Ctrl-B		D. Ctrl-F

58. 下面对Linux命令的描述哪个是正确的（   ）

A. 不是大小写敏感的					B. 都是大写的

C. 大小写敏感							D. 都是小写

59. 对文件进行归档的命令为（   ）

A dd				B cpio 				C gzip 			D tar 

60. 改变文件所有者的命令为（   ）

A chmod 			B touch 				C chown			D cat 

61. 建立一个新文件可以使用的命令为（   ）

A chmod 			B more 				C cp 			D touch 

62. 在下列命令中，不能显示文本文件内容的命令是（   ）

A more 			B less 				C tail 			D join

63. 文件权限读、写、执行的三种标志符号依次是（   ）

A rwx 			B xrw 				C rdx			D srw 

64. 设超级用户root当前所在目录为：/usr/local，键入cd命令后，用户当前所在目录为（    ）

A /home 			B /root				C /home/root 	D /usr/local

65. 系统中有用户user1和user2，同属于users组。在user1用户目录下有一文件file1，它拥有644的权限，如果user2用户想修改user1用户目录下的file1文件，应拥有权限（    ）

A 744 			B 664				C 646 			D 746

66. 如何删除一个非空子目录/tmp（    ）

A.del/tmp/* 							B.rm -rf/tmp 		

C. rm –Ra /tmp/* 					D. rm –rf /tmp/* 

 

 

二、填空题

67. 链接分为：硬链接和          。

68. 某文件的权限为：d-rw-_r--_r--，用数值形式表示该权限，则该八进制数：       。

69. 要使得名为fido的文件具有如下权限-r-xr-x—x的命令是       。

70. 在/root文件夹下查找后缀为.cpp的文件的命令是      。

71. 输入了Shell命令的部分字符后按什么键可补全其余部分:          。

72. 完全删除/tmp下的所有文件用什么命令及参数，应使用的命令是       。

73. 若从任一目录用什么命令可快速转到用户主目录      。

74. 把文件file1和file2合并成file3的命令是          。

75. 可以在标准输出上显示2012年日历的命令及参数是       。

76. 要查看目录下的所有文件的详细内容，包括隐藏文件，输入命令      。

77. 进行字符串查找，使用命令：       。

78. 使用       每次匹配若干个字符。

 

三、判断改错题

79. RedHat Linux使用 ls -all 命令将列出当前目录中的文件和子目录名。（   ）

80. 在grep命令中，有*这个通配符。（   ）

81. ls是文件显示命令。（    ）

82. rm和rmdir的作用一样，都是删除整个目录。（    ）

83. Linux 中的 ls 命令的功能是变换工作目录到目标指定目录。（    ）

84. 在linux中红色文件一般是压缩文件。（   ）

85. linux中目录文件用ls显示是绿色的。（   ）

 

四、简答题

86. linux系统中文件的概念？

87. 什么是符号链接，什么是硬链接？符号链接与硬链接的区别是什么？

88. Linux下有哪些文件类型几种，怎么区分（根据简称）？

89. 查看文本文件内容的命令主要有哪些，请列举。

90. 试解释下列信息各部分的内容：-rwxr-xr—1 root root 599 cec 10 17:12 ff ？

91. Linux系统有几种类型文件？它们分别是什么？有哪些相同点和不同点？

92. 若下达rmdir命令来删除某个已存在的目录，但无法成功，请说明可能的原因。

93. 简述more命令和less命令的区别？

 

五、操作题

94. 在当前目录/home/zheng下新建一个目录back，将当前目录改为back，在back下新建2个长度为0的文件test1、test2，然后把test2移到其父目录中并改名为file12。

95. 现在需要统计当前目录/home/zheng下普通文件的数目并显示结果,如何实现。

96. 按下列步骤写出对应命令

1）进入用户主目录，显示当前的路径。

2）复制文件/etc/group到用户主目录，文件名不变。

3）统计文件/etc/fstab的行数、单词数、字符数。

97. 目录ABC下有两个子目录a1,b2以及5个普通文件。如果想删除ABC，应使用什么命令？如何实现。

98. 写出以下命令：

1）删除文件file1

2）删除目录/dir1及其所有子文件和目录

3）复制/dir2下所有文件到/dir3目录下的命令

99. 执行命令 ls –l 时，某行显示如下：。

-rw-r--r--  1  chris  chris  207  jul 20  11:58  mydata

（1）用户chris 对该文件具有什么权限？ 

（2）执行命令useradd Tom后，用户Tom对该文件具有什么权限？

（3）如何使任何用户都可以读写执行该文件？

（4）如何把该文件属主改为用户root ？

100. 写出以下命令：

（1）创建普通文件/home/abc。

（2）修改/home/abc的属性为：属主具有一切权限，同组用户和其他用户具有可读可写的权限。

（3）显示当前的时间。



## 第三章 文本编辑

一、单项选择题

101. 在vi编辑器里，命令"dd"用来删除当前的（    ）

A. 行			B. 变量				C. 字				D. 字符

102. 在vi中，5yy表示（    ）

A．复制当前行及以下4行				B．复制当前行下面的5行   

C．粘贴当前行及以下4行				D．粘贴当前行下面的5行

103. 你在vi编辑器中对文本文件中的某行进行删除后，发现该行内容需要保留，重新恢复该行内容最佳的操作方法是（    ）

A．在编辑模式下重新输入该行			Ｂ．不保存退出vi，并重新编辑该文件

Ｃ．在命令模式下使用“u”命令			D．在命令模式下使用“.”命令

104. 在vi中，5G表示（    ）

A．将光标移到第5行的行尾      

B．将光标移到第5行的行首    

C．将光标移到本行的的第五个字符前

D．将光标移到本行的的第五个字符后

105. 在vi编辑器里，哪个命令能将光标移到第200行（   ）

A. 200g			B. :200				C. g200			D. G200

106. 在vi中退出不保存的命令是（    ）

A.:q 				B.:w 				C.:wq 			D.:q! 

107. 你使用命令“vi /etc/inittab”查看该文件的内容，你不小心改动了一些内容，为了防止系统出问题，你不想保存所修改内容，你应该如何操作（    ）

A．在末行模式下，键入:wq 		Ｂ．在末行模式下，键入:q!

Ｃ．在末行模式下，键入:q			D．在编辑模式下，键入“ESC”键直接退出vi

108. 在vi中退出不保存的命令是（    ）

A．:q					B．:w			C．:wq				D．:q!

 

二、填空题

 

三、判断改错题

109. 进入vi时，系统处于编辑模式。（   ）

 

四、简答题

110. vi编辑器有哪几种工作模式？如何在这几种工作模式之间转换？

 

五、操作题

111. 用vi编辑器打开文件f2，把第二行移动到文件末尾，删除第一和第二行并恢复删除，最后不保存修改退出。



## 第四章 Linux shell 程序设计

一、单项选择题

112. 在shell中变量的赋值有四种方法，其中，采用name=12的方法称（    ）

A 直接赋值							B使用read命令 

C 使用命令行参数					D使用命令的输出

113. 下面不具备循环功能的语句是（    ）

A．if				Ｂ．for				Ｃ．while			D．until

114. 在Shell脚本中，用来读取文件内各个域的内容并将其赋值给Shell变量的命令是（    ）

A fold			B join				C tr					D read

115. 下列变量名中有效的shell变量名是（    ）

A -2-time			B _2$3				C trust_no_1			D 2004file

116. 在一行结束位置加上什么符号，表示未结束，下一行继续？（    ）

A．\					Ｂ．/			Ｃ．:				D．|

117. 下面哪种写法表示如果cmd1成功执行，则执行cmd2命令（    ）

A．cmd1&&cmd2		Ｂ．cmd1|cmd2	Ｃ．cmd1;cmd2		D．cmd1||cmd2

118. 不是shell具有的功能和特点的是（    ）

A．管道								B．输入输出重定向   

C．执行后台进程						D．处理程序命令

119. 下列对shell变量FRUIT操作，正确的是（    ）

A．为变量赋值：$FRUIT=apple       

B．显示变量的值：fruit=apple  

C．显示变量的值：echo $FRUIT  

D．判断变量是否有值：[-f“$FRUIT”]

120. Redhat Linux默认的SHELL程序是什么（    ）

A．bash			B．tcsh 				C．ksh				D．bsh

121. 以下哪个是LINUX 管道符（    ）

A．| 				B．> 			C．>> 				D．<

122. 哪个符号加在命令后面可以在后台执行程序（   ）

A. @				B. &					C. #				D. *

123. 如果你想给变量"IQ"定义为4，下面哪些时正确的（   ）

A. IQ=4			B. set IQ=4			C. set $IQ=4		D. IQ set 4

124. 用标准的输出重定向（>）像”> file01”能使文件file01的数据（   ）

A. 被复制			B. 被移动			C. 被覆盖		D. 被打印

125. 命令 cat file.1 > file.2 的结果是（    ）

A file.2将会被file.1替换

B file.2会更名为file.1

C 将file.1的内容加入到file.2文件结尾

D将file.1的内容加入到file.2文件开头

126. 在shell环境下，使用哪个命令可以正确设置本地变量MYNAME的值为user1 good（    ）

A．MYNAME=user1 good				Ｂ．MYNAME=”user1 good” 

Ｃ．$MYNAME=user1 good				D．$MYNAME=”user1 good”

127. 想要看到命令执行后的返回值应在echo命令后使用参数（    ）

A．$#				Ｂ．$!			Ｃ．$*				D．$?

128. 某用户的主目录中有两个文本文件mail_a.txt和mail_b.txt，现在该用户想把mail_a.txt中的内容追加到mail_b.txt文件的尾部，那么应该使用（    ）

A．cat mail_a.txt > mail_b.txt		B．cat mail_a.txt < mail_b.txt 

C．cat mail_a.txt >> mail_b.txt		D．cat mail_a.txt | mail_b.txt

129. 以下哪种不是LINUX的SHELL类型（    ）

A．bash			Ｂ．ksh				Ｃ．rsh				D．csh

130. 红旗Linux系统中用户默认的Shell是（    ）

A. bash				B. ksh			C. csh				D. sh

 

二、填空题

131. 把文件file1和file2合并成file3的命令是          。

132. 编写的Shell程序运行前必须赋予该脚本文件      权限。

133. 将前一个命令的标准输出作为后一个命令的标准输入，称之为      。

134. 为脚本程序指定执行权的命令及参数是       。

135. 改变命令提示符的环境变量是       。

136. 想把文件home.txt的信息添加到last.txt文件中去，可以使用命令       。

 

三、判断改错题

137. 有两个文件test1和test2，test2有内容，现在执行cat test1>>test2，则test2文件内容被全部删除。（    ）

138. Linux中的shell命令可以分为内部命令和外部命令。（   ）

139. 在shell命令行方式下，一行只能写一个指令，每次只能使用一个命令。（   ）

140. shell中可使用alias命令定义别名。（   ）

141. shell是一个命令解释器。（    ）

 

四、简答题

142. 谈谈什么是管道？

143. Shell程序中，对用户变量赋值有哪些方式？

144. 简述Linux中shell的概念。

145. 什么是位置变量？shell的变量类型有哪些种？

 

五、操作题

146. 
（1）创建目录/mydata；

（2）进入目录/mydata；

（3）在/mydata目录下用“输出重定向”创建文本文件：student.txt。

147. 一个shell程序，要求实现：有用户输入当前用户的工作目录，显示当前目录中所有以.conf为后缀的文件，将这些后缀为.conf的文件备份到/home/public目录下。

148. 已知某整数的4个字节分别为192，168,1,254，如何拼出该整数的值，写代码表示。

149. 已知某个整数为2011，如何分别获取每个字节的大小，写代码表示。

150. 写出下述shell脚本执行的结果。当前目录为”/home/hh”。

```bash
func()

{

echo ”Let’s begin.”

echo $a $b $c 

echo $1 $2 $3

echo ”end”

}

a=”Working directory” 

b=”is”

c=‵pwd‵

func Welcome You Bye

echo ”Today is a nice day”
```


151. 写出下述shell脚本执行的结果。

```bash
for i in 1 2 3 4 5 

​    do 

​    if[“$i” -eq 3 ]

then continue

else echo “$i”

fi

done
```


152. 写出下述shell脚本exam14的执行结果。

```bash
#!/bin/bash

#script name exam14

echo  `date`

set  `date`

echo  $2 $3 $6

echo  $0 $1 $2 $3 $4 $5 $6
```


153. 阅读下面shell 程序，写出执行结果： 

```bash
#!/bin/sh 

for name in Tom Jack Harry  

do 

  echo "$name is my friend" 

done。
```


六、编程题

154. 编写一个shell脚本，能够显示下面序列的前25个数字。0,1,1,2,3,5,8,13…，前二个数字之和为第三个数字，即著名的Fibonacci序列。

155. 编写一个shell脚本，用于判别其后用参数方式指定的一系列文件是否存在。

156. 编写一个名为square的脚本程序，参数为一大于10的正整数。先检查参数是否符合要求。如果不符合要求，请给出提示；如果符合要求，输出从1到该正整数的平方值。。

157. 编写一个shell脚本，求两个数的和。

158. 创建一个shell 脚本，它从用户那里接收10个数，并显示已输入的最大的数。

159. 设计一个shell程序计算n的阶乘。最后给出计算的结果

160. 设计一个Shell程序，在/userdata目录下建立50个目录，即user1～user50，并设置每个目录的权限，其中其他用户的权限为：读；文件所有者的权限为：读、写、执行；文件所有者所在组的权限为：读、执行。

161. 编写shell程序，实现自动删除30个账号的功能。账号名的形式为stdxx，其中xx从01到30。

162. 用Shell编程，判断一文件是不是字符设备文件，如果是将其拷贝到 /dev 目录下。

163. 编写shell程序，实现自动删除50个账号的功能。账号名为stud1至stud50。

164. 编写一个名为move的脚本程序，格式move  <file1>  <file2>。如果file1不存在，给出提示；否则移动file1至file2。

165. 下面给出了一个SHELL程序，试对其行后有#（n）形式的语句进行解释，并说明程序完成的功能。

```bash
#!/bin/sh

DIRNAME=`ls /root | grep bak`										#（1）

if [ -z "$DIRNAME" ] ; then											#（2）

mkdir /root/bak ; cd /root/bak									#（3）

fi

YY=`date +%y` ; MM=`date +%m` ; DD=`date +%d`		#（4）

BACKETC=$YY$MM$DD_etc.tar.gz										#（5）

tar zcvf $BACKETC /etc													#（6）

echo "fileback finished!"
```


166. 用shell编写小九九乘法表程序，程序执行结果如下。

![99_multiplication_table](https://cdn.jsdelivr.net/gh/runlin-wang/img@master/img/99_multiplication_table.11souawo6ohs.jpg)


167. 根据下面给出的声明和数据，对每个表达式进行求值并写出他的值。在每个表达式进行求值是使用原来给出的值（也就是说，某个表达式的结果不影响后面的表达式）。假定 ints 数组在内存中的起始位置是100，整型值和指针的长度都是4 字节。

 in tints[20]={ 

  10, 20, 30, 40, 50, 60, 70, 80, 90, 100, 

  110, 120, 130, 140, 150, 160, 170, 180, 190, 200 

 }; 

 (Other declarations) 

 int *ip=ints+3;

 

| 表达式  | 值   |
| ------- | ---- |
| ints    |      |
| ints[4] |      |
| ip      |      |
| ip[4]   |      |
| *(ip+4) |      |



## 第五章 Linux内核简介

一、单项选择题

168. 内核不包括的子系统是（    ）

A 进程管理系统						B 内存管理系统 

C 文件管理系统						D硬件管理系统

169. 下列设备属于块设备的是（    ）

A．键盘			B．终端				C．游戏杆			D．硬盘

170. ./configure命令在当前目录生成供编译安装使用文件是（    ）

A．Install		B．Makefile			C．Configfile		D．Setup

171. 下面哪个选项用来添加用户定义用户登录的shell（   ）

A. －s			B. －u				C. －l			D. －sh

172. 在大多数Linux发行版本中，以下哪个属于块设备（    ）

A.串行口  	B.硬盘 				C.虚拟终端 		D.打印机 

 

二、填空题

173. Linux内核引导时，从文件      中读取要加载的文件系统

 

三、判断改错题


四、简答题

174. 进程的查看和调度分别使用什么命令。

175. 什么是线程？ 

176. 什么是进程？ 

177. Linux内核主要由哪几部分组成？

178. Linux文件系统的i节点？它包含的两部分基本参数？


五、操作题



## 第六章 常用开发工具

一、单项选择题

 

二、填空题

179. 设C语言程序my.c, 生成目标文件my.o的命令是      。

 

三、判断改错题

 

四、简答题

180. Linux软件的分发有几种方法，分别如何安装？

 

五、操作题

181. 用变量a给出下面的定义 

1)  一个指向整型数的指针（A pointer to an integer） 

2)  一个指向指针的的指针，它指向的指针是指向一个整型数（A  pointer to a pointer 

to an integer） 

3)  一个有 10 个整型数的数组（An array of 10 integers） 

4)  一个有 10 个指针的数组，该指针是指向一个整型数的（An array of 10 pointers 

to integers） 

5)  一个指向有 10 个整型数数组的指针（A pointer to an array of 10 integers）。

 

六、编程题

 

182. 编写简单的C程序，如1-n的求和，使用gcc编译，运行观察输出结果，n由键盘输入。

183. 用 C 语言编写一个源程序 main.c，用以在打开当前目录下的文件“test.txt”， 如果没有创建该文件，并使其具有读写属性。

## 第八章 Linux系统管理

一、单项选择题

184. Linux系统是一个什么样的操作系统（    ）

A．单用户、单任务					B．单用户、多任务

C．多用户、单任务					D．多用户、多任务

185. Linux的根分区的文件系统类型是（    ）

A．FAT16			Ｂ．FAT32			Ｃ．ext3				D．NTFS

186. 登录后希望重新加载fstab文件中的所有条目，我们可以以root身份执行哪个命令（    ）

A．mount –d		Ｂ．mount –c			Ｃ．mount –a			D．mount -b

187. 将光盘/dev/hdc卸载的命令是（    ）

A umount /dev/hdc 

B unmount /dev/hdc

C umount /mnt/cdrom /dev/hdc 

D unmount /mnt/cdrom /dev/hdc

188. Linux文件系统的文件都按其作用分门别类地放在相关的目录中，对于外部设备文件，一般应将其放在哪个目录中（    ）

A /bin				B /etc				C /dev				D /lib

189. Linux将存储设备和输入/输出设备均看做文件来操作，哪个不是以文件的形式出现（    ）

A 目录			B 软链接			C i节点表			D 网络适配器

190. 修改用户自身的密码可使用（    ）

A. passwd		B. passwd -d mytest	C. passwd  mytes		D. passwd -l

191. linux临时目录一般存在下面那个文件夹中（    ）

A /tmp			B /proc				C /data				D /dev

192. 在linux中有关IDE设备命名编号正确的有（    ）

A．sda  第一个 IDE 控制器，主设备

B．sdb  第二个 IDE 控制器，次设备

C．hdb  第二个 IDE 控制器，主设备

D．hda  第一个 IDE 控制器，主设备

193. 使普通用户可执行超级用户文件的命令是（    ）

A．chmod +v		Ｂ．usermod +v		Ｃ．chmod +s			D．usermod +s

194. rm -rf filename的含义（    ）

A．强行删除filename 

B．删除filename文件，删除时给予提示

C．只是针对filename进行删除

D．递归强行删除filename下的所有文件

195. ps命令显示结果中STAT的s代表（    ）

A．运行				Ｂ．休眠			Ｃ．终止				D．挂起

196. 为了达到使文件的所有者有读(r)和写(w)的许可，而其他用户只能进行只读访问，在设置文件的许可值时，应当设为（    ）

A．566				Ｂ．644			Ｃ．655				D．744

197. Linux中第一个IDE接口从盘可以表示为（    ）

A．/dev/had			Ｂ．/dev/hdb 	Ｃ．/dev/sdb 		D．/dev/sdc

198. 关于tar命令，下列说法正确的是（    ）

A．-x 参数，用于解压缩				B．-x 参数，用于还原 

C．-c 参数，用于还原					D．-c 参数，用于解压缩

199. 使用fdisk工具列出Linux支持的所有分区类型，可以使用命令（    ）

A．p				Ｂ．l				Ｃ．y				D．u

200. Linux通过VFS支持多种不同的文件系统。Linux缺省的文件系统是（    ）

A．VFAT				B．ISO9660		C．Ext系列			D．NTFS

201. Linux系统中不存在以下哪个基本文件类型（    ）

A．普通文件			Ｂ．系统文件		Ｃ．目录文件			D．链接文件

202. X Window System是（    ）

A．视窗系统		B．操作系统			C．应用系统			D．分布系统

203. 下列哪个命令可以卸载Linux文件系统（    ）

A．umount		Ｂ．ineted			Ｃ．unmount			D．mount

204. 为了查找出当前用户运行的所有进程的信息，我们可以用命令（    ）

A．ps  -a			Ｂ．ps  -u			Ｃ．ls -a 		D．ls -l

205. 以下命令可以重新启动计算机的是（    ）

A.reboot				B.halt			C.shutdown			D.init 6

206. 下列目录中存放的是日志文件的是（    ）

A./var				B./usr				C./tmp				D./var/log

207. 下面关于passwd命令说法不正确的是（    ）

A．普通用户可以利用passwd命令修改自己的密码       

B．超级用户可以利用passwd命令修改自己和其他用户的密码  

C．普通用户不可以利用passwd命令修改其他用户的密码 

D．普通用户可以利用passwd命令修改自己和其他用户的密码

208. 下面关于passwd命令说法不正确的是（    ）

A．普通用户可以利用passwd命令修改自己的密码       

B．超级用户可以利用passwd命令修改自己和其他用户的密码  

C．普通用户不可以利用passwd命令修改其他用户的密码 

D．普通用户可以利用passwd命令修改自己和其他用户的密码

209. 可查看系统中的进程ID号的命令（    ）

A．ps			Ｂ．top				Ｃ．sar				D．find

210. 使用fdisk工具建立分区默认的分区类型是（    ）

A．Linux Native	Ｂ．Linux Swap		Ｃ．FAT16			D．FAT32

211. 下列目录中与windows中的Document and settings有相同作用的目录是（    ）

A./home			B./etc				C./dev				D./tmp

212. /dev/sdc6分区表示（    ）

A.第2块IDE硬盘的第6个分区，是逻辑分区

B.第3块IDE硬盘的第6个分区，是逻辑分区

C.第3块SCSI硬盘的第6个分区，是逻辑分区

D.第3块SCSI硬盘的第2个分区，是逻辑分区

213. /dev/hdd3分区表示（    ）

A.第1块IDE硬盘的第3个分区，是逻辑分区

B.第3块IDE硬盘的第3个分区，是主分区

C.第4块IDE硬盘的第3个分区，是扩展区

D.第4块IDE硬盘的第3个分区，是主分区或扩展分区

214. Linux交换分区的挂载点是（    ）

A. /swap			B.无挂载点			C./boot				D./

215. 添加用户“user”的命令是（    ）

A.user user			B.useradd user		C.add user			D.adduser

216. 删除用户“user”及其主目录下所有文件的命令是（    ）

A.userdel -p user		B.userdel -r user	C.userdel -a user		D.userdel -z user

217. 查看系统当中所有进程的命令是（    ）

A.ps all				B.ps aix			C.ps auf				D.ps aux

218. linux临时目录一般存在下面那个文件夹中（   ）

A. /tmp			B. /proc				C. /data			D. /dev

219. 一个文件的权限是-rw-rw-r--，这个文件所有者的权限是什么（   ）

A. read-only		B. read-write		C. write			D. write-only

220. Linux系统默认使用的文件系统类型是（    ）

A.NTFS				B.FAT16			C.FAT32				D.ext3

221. 对于所有用户都能读写的文件权限是（    ）

A.777					B.444			C.644				D.640

222. 下面哪个配置文件用来定义syslog的后台进程（   ）

A. system.conf	B. syslog.conf		C. syslogd		D. slog.conf

223. Linux操作系统默认管理员账号是（    ）

A administrator	B superuser			C system				D root

224. 下列说法错误的是（    ）

A 为保证Linux文件系统的安全，把口令保存到只有超级用户才能读取的/etc/shadow文件中

B 在shadow文件中，每定义一个用户信息，行中各字段用“：”隔开

C为进一步提高系统的安全性，shadow文件中保存的是已经加密的口令

D password 是一个文本文件，用于定义系统的用户账号，该文件位于“/bin”目录下

225. 存放设备文件的相关文件目录（    ）

A. /dev			B. /etc				C. /lib				D. /bin 

226. 终止一个前台进程可能用到的命令和操作是（    ）

A kill			B ^C					C shut down			D halt

227. 若一台计算机的内存为128MB，则交换分区的大小通常是（    ）

A 64MB			B 128MB				C 256MB				D 512MB

228. 在系统重建的时候，下面哪个参数能用来对mkfs命令检查坏块（   ）

A. －b 		B. －e				C. －c			D. －check

229. Linux通过VFS支持多种不同的文件系统。Linux缺省的文件系统是（    ）

A VFAT			B ISO9660			C Ext系列		D NTFS 

230. 假设文件fileA的符号链接为fileB，那么删除fileA后，下面的描述正确的是（    ）

A.fileB也随之被删除

B.fileB仍存在，但是属于无效文件

C.因为fileB未被删除，所以fileA会被系统自动重新建立

D.fileB会随fileA的删除而被系统自动删除 

231. 哪一条命令用来装载所有在 /etc/fstab 中定义的文件系统（    ）

A. amount			B. mount –a			C. fmount		D. mount –f

232. 如何快速切换到用户John的主目录下（    ）

A.cd @John 	B.cd #John 			C.cd &John 		D.cd ~John 

233. 缺省的用户邮件放在（    ）

A.~/mail/ 							B./var/mail/ 		

C./var/mail/spool/ 					D./var/spool/mail/

234. /etc/passwd文件用来存储信息（    ）

A 系统中所有用户的加密过的密码		B 用户帐户信息和帐户的参数

C 用户和组的加密后的密码				D 所有用户和服务器的密码

235. 哪个命令专门把gzip压缩的.gz文件解压缩（    ）

A．fdisk			Ｂ．gunzip 		Ｃ．df				D．man

236. linux中配置文件放在系统的哪个目录下（    ）

A．/lib			Ｂ．/dev				Ｃ．/etc				D．/usr

237. 为了保证系统的安全，现在的linux系统一般将/etc/passwd密码文件加密后，保存为文件（    ）

A． /etc/group			B．/etc/netgroup	C． /etc/libsafe.notify	D． /etc/shadow

238. 在Linux系统中，分区hdb2 代表的含义是（    ）

A．第二个IDE的slave接口第2个主分区

B．第二个IDE的master接口第2个主分区

C．第一个IDE的slave接口第2个主分区

D．第一个IDE的master接口第2个主分区

239. Linux中充当虚拟内存的是哪个分区（    ）

A．swap				Ｂ．/			Ｃ．/boot			D．/home

240. Samba服务器的主要功能是（    ）

A．Windows 主机间的资源能够共享 

B．资源管理 

C．使 Windows 用户以及 Linux 用户能够互相访问彼此的资源 

D． Linux 主机之间实现资源共享

241. Linux支持多种文件类型，每一类用一个字符来表示，下面哪个字符表示目录（    ）

A．-				B. d					C. p					D. m

 

 

二、填空题

242. 要杀死PID是1655的进程，应使用的命令是       。

243. 需要创建一个用户账号user01，主目录为/home/user01，可以使用命令：      。

244. 要检查/dev/had1分区上的文件系统，可以使用以下命令       。

245. 前台起动的进程使用       终止。

246. 安装Linux系统对硬盘分区时，必须有两种分区类型：文件系统分区      。

247. Linux文件系统中每个文件用      来标识。

248. 设定限制用户使用磁盘空间的命令是      。

249. 在其父目录不存在时先创建父目录的命令是          。

250. 关闭linux系统（不重新启动）使用的命令是      。

251. 将光盘/dev/hdc卸载的命令是       。

252. 要强制杀死某个进程，可以使用命令      。

253. 要杀死PID是1655的进程，应使用的命令是       。

254. 需要创建一个用户账号user01，主目录为/home/user01，可以使用命令：      。

255. 要检查/dev/had1分区上的文件系统，可以使用以下命令       。

256. 检查已安装的文件系统/dev/had5是否正常，若检查有错，则自动修复，其命令及参数是        。

257. 在Linux系统下，第二个IDE通道的硬盘（从盘）被标识为：      。

258. 增加一个用户的命令是          。

 

三、判断改错题

259. Linux没有扩展分区。（   ）

260. tar可以用于备份Linux系统。（   ）

261. linux中文件系统要挂装后才能使用。（   ）

262. 拆卸文件系统的命令是"unmount"。（    ）

263. linux中文件系统要挂装后才能使用。（    ）

264. RedHat操作系统默认的文件系统是ext3。（    ）

265. Linux中权限最大的帐户是admin。（    ）

266. 块设备文件类型的标志是c。（    ）

267. Linux下，可以存在相同名称，密码不同的帐户。（    ）

268. kill向指定的进程发出特定的信号，信号0强制杀死进程。（   ）

269. 定义在/etc/fstab中的文件系统在系统启动的时候自动加载。（   ）

270. 要中断一个后台进程时，通常是使用Ctrl+c 组合键。（    ）

271. 进程可以作为一种软件资源长期保存。（    ）

272. RedHat LINUX安装时自动创建了根用户。（   ）

273. LINUX中的超级用户为root,登陆时不需要口令。（   ）

274. Linux不可以与MS-DOS、OS/2、Windows等其他操作系统共存于同一台机器上。（   ）

275. Linux是一个多用户，单任务的网络操作系统。（    ）

 

四、简答题

276. 某/etc/fstab文件中的某行如下：/dev/had5 /mnt/dosdata msdos defaults 1 2请解释其含义。

277. 什么是死锁？

278. 简述Linux设备驱动程序的基本结构？

279. 解释i节点在文件系统中的作用。

280. 什么是页式管理。

281. 进入某Linux的终端窗口后，屏幕显示abc@server:/etc$，解释其各字段意思？

282. 中断的基本概念？

283. 试述如何创建一个用户？

 

五、操作题

284. 假设你的用户账号是zheng，现在你登录进入linux系统，查看当前登录到系统中的用户,查看当前系统中运行的进程，然后再退出系统。

285. 假设你是系统管理员，需要增加一个新的用户账号zheng，为新用户设置初始密码，锁定用户账号uly，并删除用户账号chang。

286. 新建一个用户wang，密码设为123456,并将其加到root组。写出所用命令。

287. 现需添加一新用户helen并设置其用户主目录/helen，密码为空。还需要添加新组群temp，指定其GID为600，并将temp组群作为用户helen的附加组群。

288. 当前目录是/root，改变当前目录为/home，在home下建立一个student子目录，并设置请权限为属主具有全部权限、同组具有读和执行的权限、其他用户具有只读权限。

289. 新建目录/option1，并在目录下/option1下生成一文件test，文件内容任意。接着设置test文件的拥有者为jack,(jack用户已存在)，并复制test文件给/tmp目录下的test1文件。复制时保留该文件的所有属性。写出相关命令。

290. 假设已经放入光盘，设备为/dev/cdrom，请将该光盘加载到/mnt/cdrom目录下。

291. 创建一个属于新组sybase的用户sybase，密码为syb123，请写出需要执行的命令。

292. 分别写出命令

1）查找并输出/etc/password 文件下所有含sybase的所有行的内容;

2）查找并输出/etc/fstab 文件下所有不含default的所有行的内容。

293. 根据以下步骤写相应命令：

1）创建一个以abc命名的用户。

2）添加一个用户组，名称为grp123。

3）修改新建的用户属于grp123组。

4）复制文件/etc/passwd到用户主目录，文件名称不变。

294. 写出以下命令：

（1）创建一个以zhangsan命名的用户。

（2）添加一个用户组，名称为js。

（3）修改新建的用户zhangsan属于js组。

295. 先创建mygroup组群，再创建myuser用户，并且此用户属于mygroup组群。

296. 现有一个Windows下使用过的U盘（U盘使用/dev/sda1接口），要求在此U盘上新建myfiles目录，并在此目录下新建一文件soft，内容任意，再将该文件复制到/root目录下，最后安全取出U盘。写出相关命令。

 

## 第九章 网络应用及管理

一、单项选择题

297. 下列提法中，不属于ifconfig命令作用范围的是（    ）

A 配置本地回环地址 					B 配置网卡的IP地址

C 激活网络适配器 					D 加载网卡到内核中

298. 下列文件中，包含了主机名到IP地址的映射关系的文件是（    ）

A /etc/HOSTNAME					B /etc/hosts  

C /etc/resolv.conf						D /etc/networks

299. 要配置NFS服务器，在服务器端主要配置文件（    ）

A /etc/rc.d/rc.inet1	B /etc/rc.d/rc.M		C /etc/exports			D /etc/rc.d/rc.S

300. 为了查看某接口是否正在工作，我们可以使用（    ）

A．ifup				Ｂ．alias			Ｃ．netcfg			D．ifconfig

301. 下面哪个文件定义了网络服务的端口（    ）

A．/etc/netport			Ｂ．/etc/services	Ｃ．/etc/server		D．/etc/netconf

302. route命令中-net 是指（    ）

A．目标是一个网段					B．目标是一个主机 

C．目标是所有网段					D．目标是所有主机

303. 配置主机网卡IP地址的配置文件是（    ）

A./etc/sysconfig/network-scripts/ifcfg-eth0	B./etc/sysconfig/network

C./etc/resolv.conf						D./etc/host.conf

304. . 指定系统主机名的配置文件是（    ）

A./etc/hosts							B./etc/host.conf		

C./etc/sysocnfig/network					D./etc/resolv.conf

305. 下列提法中，不属于ifconfig命令作用范围的是（    ）

A 配置本地回环地址					B 配置网卡的IP地址 

C 激活网络适配器						D 加载网卡到内核中

306. 在局域网络内的某台主机用ping命令测试网络连接时发现网络内部的主机都可以连同，而不能与公网连通，问题可能是（    ）

A 主机IP设置有误 

B 没有设置连接局域网的网关 

C 局域网的网关或主机的网关设置有误 

D 局域网DNS服务器设置有误

307. 当我们与某远程网络连接不上时，就需要跟踪路由查看，以便了解在网络的什么位置出现了问题，满足该目的的命令是（    ）

A ping 			B ifconfig 			C route 				D netstat

308. 激活或关闭Linux网络接口时要使用的命令是（    ）

A.enable			B.disable			C.netconfig		D.ifconfig 

309. /dev/ethX代表（    ）

A．系统回送接口	Ｂ．以太网接口设备 Ｃ．令牌环网设备		D．PPP设备

310. 配置主机网卡IP地址的配置文件是（    ）

A./etc/sysconfig/network-scripts/ifcfg-eth0

B./etc/sysconfig/network

C./etc/resolv.conf

D./etc/host.conf

 

二、填空题

311. 欲测试与主机 www.baidu.com 的连通性，应使用的命令和参数是：        。

312. Sendmail邮件系统使用的两个主要协议是： SMTP 和 POP ，前者用来发送邮件,后者用来       。

 

三、判断改错题

313. pop3使用的tcp端口为110。（   ）

314. UDP协议是一种无连接的协议，它可以提供可靠的数据传输。（   ）

315. 在Linux中，一个网卡可以绑定多个Ip地址。（    ）



四、简答题

316. 给出命令 ping 200.111.23.5 -c 3000的含义是什么？

317. 简述网络文件系统NFS，并说明其作用。

318. 什么是netstat命令？

319. 写出以下对应的命令：

（1）查看当前主机的路由的命令。

（2）配置当前主机的默认网关为192.168.2.254的命令。

（3）连续ping目的IP为192.168.2.245为10次的的命令。

（4）查看当前主机TCP协议连接情况的命令。

320. 配置网卡eth0的IP地址为192.168.10.1，子网掩码为255.255.255.0。



五、操作题
