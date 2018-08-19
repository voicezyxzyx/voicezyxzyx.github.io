---

title:  pycharm联网不能登陆的激活问题
categories: Python
tags: [pycharm,pycharm激活]

---

#### windows

进入C:\Windows\System32\drivers\etc，找到hosts文件，复制一份到桌面，然后进行编辑，将下面的内容粘贴到最后，并保存，然后把文件放回源目录，替换之前的文件。

 0.0.0.0         account.jetbrains.com 

然后重新激活对应的pycharm即可。 

#### Linux

输入下面的命令， 

sudo vi /etc/hosts

打开host文件，打开之后，将  

0.0.0.0         account.jetbrains.com 

粘贴到最后，并保存，

然后重新激活对应的pycharm即可。 