﻿1， cd : change directory的简写，改变目录的意思，就是切换到哪个目录下， 如 cd e:\fff  切换 E 盘下面的fff 目录。

　　当我们用cd 进入文件夹时,我们可以使用 通配符*, cd f*,  如果E盘下只有一个f开头的文件夹,它就会进入到这个文件夹.

2， cd .. 回退到上一个目录。我们在写js,或css时，我们引入文件时，.. 表示的就是上一个目录, 所以 cd .. 回退到上一个目录就很好理解了。注意，cd 和两个点点..之间有一个空格,  

3， pwd : print working directory, 打印工作目录，它会显示我们当前所在的目录路径。

4， ls: list, 列出当前目录中的所有文件，     只不过ll(两个ll)列出的内容更为详细。

5， touch : 新建一个文件 如 touch index.js 就会在当前目录下新建一个index.js文件。

6，rm:  删除一个文件, rm index.js 就会把index.js文件删除.

7,  mkdir: 新建一个目录,就是新建一个文件夹. 如mkdir src 新建src 文件夹.

8,  rm -r :  删除一个文件夹， r (recusive 是递归的意思)， 删除用的就是递归，先删除文件夹里面的内容，再删除文件夹。 rm -r src 删除src目录。 

9,  mv 移动文件, mv index.html src   index.html 是我们要移动的文件, src 是目标文件夹,当然, 这样写,必须保证文件和目标文件夹在同一目录下.

10, reset 清屏，把git bash命令窗口中的所有内容清空。