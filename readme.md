# 导入我的扩展

浏览器地址栏输入 arc://version/ 并回车

复制个人资料路径并填写到文件管理器地址栏 并回车 

复制Extensions到个人资料路径并选择替换同名文件

# Arc重启脚本使用方法

1.导航到test/restart.py 用记事本/vscode打开

2.修改process_name为arc.exe

3.修改program_path为arc.exe在文件夹中的位置

-按win键然后搜索arc，选择打开文件位置，跳转到快捷方式的位置

-再次右击快捷方式打开文件所在的位置

-复制此时打开的文件夹中arc.exe的路径（复制文件地址），并填入program_path

4.保存restart.py

5.（需自行安装python并pip install pyinstaller）

打开cmd并执行

pyinstaller --onefile restart_program.py

以此编译py文件，之后导航到test/dist/restart.exe,双击运行restart.exe便可快速清除后台并重启arc。

# 配置文件

configfile文件夹中装的是油猴脚本和stylus的配置文件，根据需求导入

### 日常使用
新建标签页：Ctrl + T

新建窗口：Ctrl + N

关闭当前标签页或窗口：Ctrl + W

重新打开最后关闭的标签页：Ctrl + Shift + T

固定/取消固定当前标签页：Ctrl + D

复制当前标签页网址：Ctrl + Shift + C

更改当前标签页网址：Ctrl + L

显示/隐藏侧边栏：Ctrl + S

清除未固定的标签页：Ctrl + Shift + K

撤销：Ctrl + Z

### 快速导航
直接前往第N个收藏夹：Ctrl + 1, Ctrl + 2, Ctrl + 3, ...

直接前往第N个空间：Alt + 1, Alt + 2, Alt + 3, ...

在最近的标签页间切换：Ctrl + Tab

添加分屏视图：Ctrl + Shift + +

添加特定链接到分屏视图：Alt + 左键点击链接

在预览中打开链接：Shift + 左键点击链接

### 其他命令
放大网页：Ctrl + +

缩小网页：Ctrl + -

重置网页缩放：Ctrl + 0

查找文本后的下一个匹配项：Ctrl + G

查找文本后的上一个匹配项：Ctrl + Shift + G

重新加载网页：Ctrl + R

在网页中查找：Ctrl + F

下载管理：Ctrl + J

设置：Ctrl + ,

全屏： (Fn) + F11

查看历史记录：Ctrl + H

