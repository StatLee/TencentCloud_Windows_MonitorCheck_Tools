# TencentCloud_Windows_MonitorCheck_Tools
腾讯云检测WIndows Server巴拉多监控上报情况GUI工具

功能简述： 腾讯云Windows Server上默认安装巴拉多监控用作上报OS类各种性能监控数据并体现在腾讯云云监控产品中，通常发现腾讯云Windows Server CVM监控中断时可以通过该工具检查巴拉多监控是否正常运行，以便于快速排障

开发语言：

PowerShell v2.0

适用平台：

Windows Server 2008 R2 、 Windows Server 2012/2012R2 、 Windows Server 2016/2019 Wndows 7 SP3、Windows 8、Windows 10

版本：v1.2.1

功能信息：

1、支持自定义 进程、NTP、telnet 测试信息

2、支持逐项检查测试项

3、可视化的测试过程

4、支持测试结果、日志一键导出方便上报给腾讯云客服

下载成品链接：

https://platform01-1252076932.cos.ap-chengdu.myqcloud.com/statli_tools/Barad_Agent_Check_For_Windows_v1.2.1.exe

若运行时闪退可能是因为PowerShell策略限制，可手动运行该命令进行解锁：

powershell "Set-ExecutionPolicy -ExecutionPolicy Unrestricted -force |Out-null"
