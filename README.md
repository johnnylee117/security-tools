# security-tools
## iov and cyber security tools 

一、ide-eval-resetter-2.1.6.zip  
1.用途：用于pycharm永久激活  
2.使用步骤
* 下载完成后，将 zip 插件包拖入 IDE 界面中。如果无法拖动安装，你可以在Settings/Preferences... -> Plugins 里手动安装插件（Install Plugin From Disk...）
* PS: macOS 系统可能会自动解压，然后把zip包丢进回收站, 需要注意以下~插件安装成功后，右下角会提示安装成功。同时安装成功之后在菜单栏  Help  中会多一个  Eval Reset 按钮。点击之后会出现三个按钮。
* 勾选项： Auto reset before per restart 如果勾选了，则自勾选后每次重启/退出IDE时会自动重置试用信息，你无需做额外的事情。（此为自动重置方式）按钮：
* Reload 用来刷新界面上的显示信息。
* Reset 点击会询问是否重置试用30天并重启IDE。选择Yes则执行重置操作并重启IDE生效，选择No则什么也不做。（此为手动重置方式）
* 使用方法安装插件之后，勾选  Auto reset before per restart  之后点击 Reload 再点击  Reset 重启即可。说明：目前来讲，这是一个最稳定的“激活”方式，没有之一。重启PyCharm时 会自动重置如果25天没有任何重置动作，则会通知是否进行重置如果勾选Auto reset before per restart ，静默重置理论上，勾选了Auto reset before per restart 之后无需再管，一劳永逸
* 注1：这个插件只是无限制的刷新试用时间，今天打开试用期30天，明天打开还是试用期30天，后台还是30天，大后天... 大大后天...
* 注2：在使用的时候发现偶尔不会自动重置，只需要手动点击    Reload 然后  Reset 即可
