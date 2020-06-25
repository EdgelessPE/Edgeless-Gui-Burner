# Edgeless-gui-maker

码云/Gitee： <https://gitee.com/Billraozihan/Edgeless-gui-maker>  

本家： [Edgeless PE](https://home.edgeless.top/)

> 重点：压缩包里的 startme.bat/运行我.bat 的开源协议不是 Unlicense！此文件按照 AGPL V3 协议开源。压缩包内的一切 exe 程序均按照原作者发布时的协议开源/闭源！  

下载中 exe 后缀的是加壳打包好的单文件程序，bak 后缀的是可解压查看源码的版本。

# 注意：非 win10 系统运行时报错请先尝试 [ 安装ie11 ]( https://support.microsoft.com/zh-cn/help/18520/download-internet-explorer-11-offline-installer ) 。

目前功能：
- 使用 HTML 制作的图形化界面，打包为 hta 应用。模板来自 Hexo 的默认主题 landscape
- 完美支持传统和 uefi 双启动方式
- 可选双分区方案，exfat 分区存放大文件
- 双分区下启动分区隐藏
- 完整的日志 (js.html)

这个工具的大致原理是使用 ActiveX 运行 cmd 命令来操作U盘，因其中使用的一个小工具使用了加壳加密，所以可能会被杀软误报。建议在下载和使用过程中暂时关闭杀毒软件（特别是 Windows defender！）如不信任，可使用虚拟机运行这个工具（未测试功能是否正常）。


效果图：  
![img]( https://github.com/Billraozihan/Edgeless-gui-maker/blob/master/1.png?raw=true )  
![img]( https://github.com/Billraozihan/Edgeless-gui-maker/blob/master/2.png?raw=true )  
![img]( https://github.com/Billraozihan/Edgeless-gui-maker/blob/master/3.png?raw=true )  
