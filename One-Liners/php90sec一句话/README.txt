﻿[+] 说明
[1] 文件名:	90sec.php
[2] md5:	9D2B0787ABC145778240E30BEFB47F50
[3] 性质:	php一句话木马

[+] 特点
[1] 过D盾 (科普:D盾属于伪静态查杀,目前国内最好的web木马查杀工具,查杀率极高,误报率极低!查杀技巧令人敬佩!)
[2] 过安全狗 (科普:安全狗属于完全静态查杀,查杀率不高,误报率很大,正则不完善,较易突破!)
[3] 过智创防火墙 (说明:未对该防火墙进行研究,经习科群里数个基友测试,可突破该web防火墙)
[4] 理论上过国内任何waf和防火墙 (科普:该木马的免杀方式已经不是国内web安全产品所能理解的!)

[+] 其它
[1] 默认连接后修改本身为只读权限0444(防止被删除)

[+] 连接
[1] 菜刀连接方式1: 配置填 <O>key=90sec</O> , 密码: shellcode (见图片LOOKME1.png)(推荐的连接方式!post提交方式不会在apache和ngix的日志中记录,非常利于木马隐藏)
[2] 菜刀连接方式2: ?key=90sec , 密码: shellcode (见图片LOOKME2.png)(不推荐的连接方式,会留下可以日志记录,不利于key的隐藏)
[3] 科普:安全狗对菜刀的封包进行的过滤,所以出现403不是是木马不免杀,而是菜刀的发包方式不免杀,修改菜刀即可,参考:https://forum.90sec.org/forum.php?mod=viewthread&tid=5722

[+] 作者
[1] www.90sec.org
[2] L34Rn_H4ck_Team

[+] mst
[1] 国产web渗透测试平台,专注WebExp
[2] http://mstoor.duapp.com/

[+] 免责
[1] 仅提供技术交流,使用造成的后果使用者自负