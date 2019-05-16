# Windows 10 开发环境自动配置
[English Version](https://github.com/FaintGhost/EnvSetup/edit/master/README_EN.md)
该脚本fork自Edi Wang用来快速配置一个全新的开发环境. 您可以修改脚本以满足您自己的需求。

## 前置条件

- 全新安装的 Windows 10 专业版 1903
- 如果你在中国，“稳定”的网络连接

> 该脚本没有的其他版本的Windows上测试过, 如果您在其他Windows版本上使用它风险自负

## 如何使用

### 可选

将“Add_PS1_Run_as_administrator.reg”导入注册表，以便使用管理员身份运行PowerShell脚本。

### 使用管理员身份运行 Install.ps1

- 设置一个新的计算机名
- 接入外部电源时永不睡眠
- 在桌面添加“此电脑”图标 (需要刷新桌面)
- 从桌面删除"Microsoft Edge"快捷方式
- 为Windows安装Chocolatey (这里使用packages.config文件来配置所需要安装的软件及指定版本号）
    - Google Chrome
    - Pot Player
    - TeamViewer
    - Notepad++
    - Visual Studio Code
	- jdk8
	- intellijidea-ultimate
    - Git
	- dejavufonts
	- python
	- tim
	- dropbox
	- nextcloud-client
- 卸载一些预载的UWP应用
    - Messaging
    - CandyCrush
    - Bing News
    - Solitaire
    - People
    - Feedback Hub
    - Your Phone
    - My Office
    - FitbitCoach
    - Netflix
