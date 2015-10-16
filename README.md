CheckIpTools
============

集成 checkgoogleip，python(带netaddr)，以及一些实用的小工具。
源代码取自 [checkgoogleip](https://github.com/moonshawdo/checkgoogleip)、[XX-Net](https://github.com/XX-net/XX-Net)、双手码出，感谢大家的辛勤付出！


目录文件说明：
 * !ptools.bat          转换IP小工具，输入相应编号进行操作
 * !ptools.py           代码文件，Linx 命令 $ python !ptools.py
 * checkip.bat          用于扫描谷歌IP工具的工具
 * checkip.py           代码文件，Linux 命令 $ python checkip.py，修改说明参考：[README2.md](https://github.com/xyuanmu/checkiptools/blob/master/README2.md)
 * googleip.ip.txt      已转换成CIDR格式的IP段，可用于 [XX-Net](https://github.com/XX-net/XX-Net) 或者 GoGo Tester
 * googleip.txt         已转换成 xxx.xxx.xxx.xxx-xxx.xxx.xxx.xxx 格式的IP段，可用于 [XX-Net](https://github.com/XX-net/XX-Net)
 * ip_range_bad.txt     包含IP段黑名单的文件，支持 checkgoogleip IP组格式，支持 # 注释
 * ip_range_origin.txt  包含原始IP段的文件，支持 checkgoogleip IP组格式，支持 # 注释，**以后只需将新IP段添加进来用 !ptools.bat 转换即可**
 * enjoy it!

工具预览：
![checkiptools](https://cloud.githubusercontent.com/assets/12442896/10535644/0fdd23dc-7417-11e5-885c-ba02b03b0ab1.png)

## 20151016更新
* 增加工具选项，更直观
* 增加导出 ip_tmpok.txt 为XX-Net格式，便于复制到 data/gae_proxy/good_ip.txt
* 增加IP格式互转 GoAgent <==> GoProxy
* **新版本包含中文字符，出现乱码[请下载1.0版](https://github.com/xyuanmu/checkiptools/releases/tag/1.0)，[使用说明](https://github.com/xyuanmu/checkiptools/blob/1.0/README.md)。**