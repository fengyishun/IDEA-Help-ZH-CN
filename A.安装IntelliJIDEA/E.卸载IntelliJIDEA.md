# 卸载IntelliJ IDEA

### 目录

- [ToolboxApp工具箱](#ToolboxApp工具箱)
- [单独工具](#单独工具)
- [静默卸载](#静默卸载)
- [Snap包(linux)](Snap包(linux))

&nbsp;

最正确的卸载方法取决你的安装方法。

`这份指南会告诉你Winddows上的卸载方式`

## ToolboxApp工具箱

如果你是通过Toolbox App安装的：

打开Toolbox App，点击对应的实例图标，选择 **Uninstall**。

![alt](<https://github.com/fengyishun/IDEA-Help-ZH-CN/blob/master/resources/toolbox_app_uninstall_win.png>)



## 单独工具

移除单独工具实例，用你当前操作系统的常规方式去卸载应用然后删除之前安装的文件夹。

1. 在 **Settings**里面打开 **Apps & features**选项。

2. 选择 IntelliJ IDEA app 点击 **Uninstall**。

3. 删除以下文件夹：

   | 配置文件                                        | 系统文件                                       |
   | ----------------------------------------------- | ---------------------------------------------- |
   | %HOMEPATH%\.<product><version>\config           | %HOMEPATH%\.<product><version>\system          |
   | 示例:C:/Users/JohnS/\.IntelliJIdea2019.1/config | 示例:C:/Users/JohnS/.IntelliJIdea2019.1/system |





## 静默卸载

如果你使用静默安装方式安装的话，你可以用管理员身份用 **/S**开关运行卸载程序。卸载程序位于安装目录的bin下。

Windows下以管理员身份打开cmd，cd到安装目录，执行下面的命令：

`bin\uninstall.exe /S`

&nbsp;

[回到顶部](#目录)

[< 上一节　更新IntelliJ IDEA](/A.安装IntelliJIDEA/D.更新IntelliJIDEA.md)  　　　　　　　　　　　　　　　　　　　　　　　　[下一节　入门指南 >](/B.入门指南/A.入门指南.md)

&nbsp;

　　　　:star::star::star::star::star::star::star::star::star::star::star::star::star::star::star::star::star::star::star::star::star::star::star::star::star::star::star::star:

