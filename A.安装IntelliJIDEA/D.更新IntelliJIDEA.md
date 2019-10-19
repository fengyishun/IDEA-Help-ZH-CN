# 更新IntelliJ IDEA

### 目录

- [Toolbox App(工具箱)](#ToolboxApp(工具箱))
- [单独工具](#单独工具)

&nbsp;

默认地，IntelliJ IDEA会自动检查更新并且如果有新的可用的版本会通知你。更新都是基于补丁的，它们会应用到你现有的安装实例中去，重启后生效。



## ToolboxApp(工具箱)

如果你是通过Toolbox App 安装的IntelliJ IDEA，若有新的可用版本时会建议你更新。

如果你想让它自动更新被托管的工具：

1. 打开Toolbox App并点击右上角那个类似于螺母的设置按钮。
2. 选择**Update all tools automatically**。



你可以为每个托管的工具分别设置它们的更新方式。

1. 打开Toolbox App，点击需要的工具图标并选择**Settings**。
2. 选择是否保持当前的主要版本、自动更新以及选择更新渠道：
   - **Release**：仅更新产品推荐的稳定版本。
   - **Release and EAP** ： 更新beta版本、候选版本以及“抢先体验计划”中的版本。不推荐在生产中使用。
   - **Release, EAP, and Nightly**：高度不稳定的灰度版本。



## 单独工具

如果你是手动安装的IntelliJ IDEA则由它自己来管理更新配置。当有新版本可用时会提醒你更新。你可以选择更新现有的实例、下载并安装新的版本作为一个新的实例、推迟通知或者完全忽略更新。

![alt](<https://github.com/fengyishun/IDEA-Help-ZH-CN/blob/master/resources/ij_update_restart.png>)

&nbsp;

你可以在 **Settings/Preferences**（ctrl + alt + s）首选项面板中的 **Appearance and Behavior | System Settings**的**Updates** 选项来管理IDEA 的更新配置。

#### 手动检查更新

如果你禁用了自动检查更新，点击Check Now按钮看看是否有新版本可用。

或者你可以在主菜单中检查更新：

- Windows和Linux：**Help | Check Updates**
- macOS: **IntelliJ IDEA | Check for Updates**

​	

#### 检查更新渠道

 使用更新渠道列表来限制你想使用的版本。

`你可以只选择你在用的稳定版本，因为“抢先体验计划”，渠道总是被设置成获取最新版本。`

- **Early Access Program**：提供所有的更新，包含主要版本的体验版和次要版本的预览版。不推荐在生产开发中使用这个渠道。

  `IDEA只能更新为次要预览版本而不能更新为主要EAP版本。比如，你可以将2017.2.3更新到2017.2.4 EAP，但不能更新到2017.3 EAP。这种情况下的2017.3 EAP版本将作为附加实例安装。EAP版本可以升级成较新的EAP版本和稳定的IDEA版本。如果一个EAP版本升级到稳定版本，原始的安装文件的目录名称不会改变。`
  
- **Beta Releases or Public Previews**：包括稳定发布版、发布候选版和测试版。该渠道的一些更新可能会有一些小bug和功能预览。

- **Stable Releases**：只有推荐用于生产的稳定版本。



#### 查看并管理忽略更新

因为某些原因你决定忽略建议更新，当你改变主意的时候你可以再次查看到每个被你忽略掉的更新并且恢复它们。

1. 点击**View/edit ignored updates** 链接。忽略更新对话框会列出当前被忽略的清单。

2. 如果你确定让某个更新生效，从这个清单中将其删除即可。

   `如果你从清单中删除了一些更新，当你检查更新的时候只会提供最新的下载。`



#### 使用安全连接

IDEA默认使用HTTPS下载更新，如果你使用不安全的HTTP，取消**Use secure connection**选项。

`HTTP可能会因为安全原因被阻止连接`



#### Snap包

如果你是用Snap Package方式安装的IDEA，它将会自动管理更新。所有的Snap应用每天都会自动在后台更新。你也可以使用下面命令在任何时间手动获取最新的版本：

`$ sudo snap refresh`

如果你只向更新IntelliJ IDEA：

| 旗舰版                                     | 社区版                                      |
| ------------------------------------------ | ------------------------------------------- |
| $ sudo snap refresh intellij-idea-ultimate | $ sudo snap refresh intellij-idea-community |

&nbsp;

[回到顶部](#目录)

[<上一节　注册IntelliJ IDEA](/A.安装IntelliJIDEA/C.注册IntelliJIDEA.md)   　　　　　　　　　　　　　　　　　　　　　　　　　[<下一节　卸载IntelliJ IDEA](/A.安装IntelliJIDEA/E.卸载IntelliJIDEA.md)

&nbsp;

　　　　:star::star::star::star::star::star::star::star::star::star::star::star::star::star::star::star::star::star::star::star::star::star::star::star::star::star::star::star:

