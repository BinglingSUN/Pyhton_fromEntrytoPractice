# 第一部分：基础知识

## 第1章  起步
1. 在windows系统中搭建Python编程环境

* 步骤1：python3安装包下载，链接http://python.org/downloads/

* 步骤2：安装和配置环境变量，参考连接https://www.runoob.com/python3/python3-install.html

  在环境变量中添加Python目录：在命令提示框中(cmd) : 输入如下命令，再按下 "Enter"。**注意:** C:\Python 是Python的安装目录。

  ``` 
  path=%path%;C:\Python 
  ```

  也可以通过以下方式设置：

  ``` 
右键点击"计算机"，然后点击"属性"
  
  然后点击"高级系统设置"
  
  选择"系统变量"窗口下面的"Path",双击即可！
  
  然后在"Path"行，添加python安装路径即可(我的D:\Python32)，所以在后面，添加该路径即可。 **ps：记住，路径直接用分号"；"隔开！**
  
  最后设置成功以后，在cmd命令行，输入命令"python --version"或"python"，就可以有相关显示。 查看python版本命令：python --version 或者 python
  ```
  
* 步骤3：安装文本编辑器如：pycharm

  PyCharm 下载地址 : https://www.jetbrains.com/pycharm/download/

  PyCharm 安装地址：[http://www.runoob.com/w3cnote/pycharm-windows-install.html](https://www.runoob.com/w3cnote/pycharm-windows-install.html)

## 第2章  变量和简单数据类型

### 2.1 变量

*在程序中可随时修改变量的值，而python始终记录变量的最新值。*

```python
输入:  message = 'hello world!'
	  message = 'hello python world!'
	  print (message)
输出:  hello python world!
```

#### 2.1.1 变量的命名和使用

* 变量名只能包括字母、下划线和数字。可变量名可以字母或下划线开头，但不能以数字开头。
* 变量名不能包含空格，但可使用下划线来分隔。
* 不要将python关键字和函数名用作变量名，如print。
* 变量名应既简短又具有描述性。
* 慎用小写字母l和o，因为太像数字1和0。
* 避免使用大写字母是个不错的选择。
