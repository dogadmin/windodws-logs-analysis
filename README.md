# windodws-logs-analysis
# windows日志一键分析小工具

## 使用方法

考虑到一些因素，写了个基于.net 4.0的LogParser Windows日志一键分析小工具。所以在使用得时候需要在相同目录放入LogParser.exe即可，使用得时候记得管理员权限运行

可以快速的进行一些日志分析，后续也会慢慢的进一步进行更新。可以帮助一些用户快速的针对服务器日志进行分析发现。


2020-04-27更新，删除一些不必要规则，修复部分bug,优化实在丑的不行的UI。

2020-05-15更新，增加开关机日志规则。

2020-10-13更新，增加本地日志分析版本。先更新固定路径，路径为C:\\log，需要把分析的evtx日志放到该目录下面。同时增加mssql爆破日志分析功能以及是否本机存在挖矿木马功能

2020-12-2更新，修改了远程桌面日志显示其他登录类型，只显示rdp成功登录，不显示其他杂音
