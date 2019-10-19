### 目录

- [安装IntelliJ IDEA](#安装IntelliJIDEA )
- [系统要求](#系统要求)
- [使用工具箱安装](#使用工具箱安装)
- [单独安装](#单独安装)
- [静默安装](#静默安装)





## 安装IntelliJIDEA 

**IDEA是一个能够在Windows、macOS和Linux操作系统上提供一致体验的跨平台的IDE。**

这份指南描述了在Windows上安装的方式。

IDEA有以下版本可用：

- 社区版是免费且开源的，Apaceh2.0开原许可。它提供了JVM和Android开发的基本功能。

- 旗舰版是收费的，但有30天体验期。它为Web企业开发提供了额外的工具和功能。

了解更多，https://www.jetbrains.com/idea/features/editions_comparison_matrix.html





## 系统要求

| 名称     | 最低配置           | 推荐配置                    |
| -------- | ------------------ | --------------------------- |
| 内存     | 2GB                | 8GB                         |
| 硬盘     | 1.5GB，缓存需要1GB | 固态硬盘且至少有5GB可用空间 |
| 显示器   | 1024x768           | 1920×1080                   |
| 操作系统 | 最低Win7           | 最新的64位版本              |

`您不需要再安装Java即可运行IDEA，因为JRE1.8已经绑定了IntelliJ IDEA。但是要开发一个Java应用还需要有一个独立的JDK。`





## 使用工具箱安装

安装JetBrains 的产品推荐使用JetBrains Toolbox App（工具箱）。使用它来安装和维护不同产品或者同一产品的不同版本，包含最早的EAP版本，必要时升级或者回滚，并且方便的移除任何工具。工具箱维护着你所有的项目列表，可以让你快速的打开任何项目，并且能确保项目的IDE类别和版本的正确性。

### 安装工具箱

1. 下载安装文件 <https://www.jetbrains.com/toolbox/app/>。

2. 运行安装文件并按步骤安装。

   运行起来之后，点击提示区域的图标并选择你想安装哪个产品哪个版本。

   ![alt](<https://github.com/fengyishun/IDEA-Help-ZH-CN/blob/master/resources/toolbox_app_win.png>)





## 单独安装

手动安装IntelliJ IDEA可以管理每个实例和所有的配置文件。比如说您需要将它安装在特定的路径。

1. 下载安装包 [https://www.jetbrains.com/idea/download/](https://www.jetbrains.com/idea/download/ "下载")

2. 运行安装文件并按步骤安装。

   `32位的操作系统的JRE没有绑定IntelliJ IDEA。如果您用的Windows 32位系统，请在安装向导里选择“下载并安装JRE x86 JetBrains”选项。`





## 静默安装

静默安装没有任何用户界面。网络管理员可以在多台机器上安装并避免打扰到其他用户。

若想静默安装，按下面步骤运行安装文件：

- /S:  启用静默安装
- /D:  指定安装目录的路径
- /CONFIG: 指定静默配置文件的路径 

举个栗子：

` ideaIU.exe /S /CONFIG=d:\temp\silent.config /D=d:\IDE\IntelliJ IDEA Ultimate`

**静默配置文件**

您可以为IntelliJ IDEA 下载静默配置文件  <https://download.jetbrains.com/idea/silent.config>

静默配置文件定义了安装IntelliJ IDEA的操作。默认只对当前用户（mode=user）执行静默安装。如果您想给所有的用户安装IntelliJ IDEA，用编辑器打开静默配置文件，改变安装模式参数（mode=admin）的值并且以管理员身份运行安装文件。

`默认静默配置文件是JetBrains 产品独一无二的特点。您可以根据需要修改各种安装选项可用或者禁用。`

​																																		



[回到顶部](#目录)



　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　[下一节　第一次运行IDEA >](/A.安装IntelliJIDEA/B.第一次运行IDEA.md)