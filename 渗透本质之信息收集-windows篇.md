# 信息广度收集：
## Whois信息
+ 站长之家：http://whois.chinaz.com
+ Bugscaner：http://whois.bugscaner.com
+ 国外在线：https://bgp.he.net
## 一级域名
+ 企查查：https://www.qichacha.com
+ 天眼查：https://www.tianyancha.com
## 子域名
+ OneForAll：https://github.com/shmilylty/OneForAll
+ ksubdomain：https://github.com/knownsec/ksubdomain
+ subDomainsBrute：https://github.com/lijiejie/subDomainsBrute
+ Sublist3r：https://github.com/aboul3la/Sublist3r
+ RappidDns：https://rapiddns.io/subdomain (在线)
+ 查子域：https://chaziyu.com/ (在线)
## 旁站
+ 在线：http://stool.chinaz.com/same
+ 在线：https://site.ip138.com
## 真实ip
+ 全球ping：https://www.wepcc.com
+ dns检测：https://tools.ipip.net/dns.php
+ Xcdn：https://github.com/3xp10it/xcdn
+ 在线：https://ipchaxun.com
## 端口+C段
+ Nmap：https://nmap.org
+ masscan：https://github.com/robertdavidgraham/masscan
+ Goby：https://gobies.org
+ 御剑：https://github.com/foryujian/yujianportscan
## 敏感信息
### googlehack语法
1. 后台地址
+ site:xxx.com 管理后台/登陆/管理员/系统
+ site:xxx.com inurl:login/admin/system/guanli/denglu
2. 敏感文件
+ site:xxx.com filetype:pdf/doc/xls/txt
+ site:xxx.com filetype:log/sql/conf
3. 测试环境
+ site:xxx.com inurl:test/ceshi
+ site:xxx.com intitle:测试
4. 邮箱/QQ/群
+ site:xxx.com 邮件/email
+ site:xxx.com qq/群/企鹅/腾讯
+ site:xxx.com intitle:"Outlook Web App"
+ site:xxx.com intitle:"mail"
+ site:xxx.com intitle:"webmail"
5. 其他
+ site:xxx.com inurl:api
+ site:xxx.com inurl:uid=/id=
+ site:xxx.com intitle:index.of "server at"
### Github
+ @xxx.com password/secret/credentials/token/config/pass/login/ftp/ssh/pwd
+ @xxx.com security_credentials/connetionstring/JDBC/ssh2_auth_password/send_keys
### 网盘引擎
+ 盘搜搜：http://www.pansoso.org
+ 盘多多：http://www.panduoduo.net
+ 大力盘：https://dalipan.com
## 空间引擎搜索
+ FOFA：https://fofa.so
+ Quake：https://quake.360.cn/quake/#/index
+ Shadon：https://www.shodan.io
+ ZoomEye：https://www.zoomeye.org
## 历史漏洞
+ 乌云镜像：https://wooyun.x10sec.org
+ Seebug：https://www.seebug.org
+ Exploit Database：https://www.exploit-db.com
+ Vulners：https://vulners.com
+ Sploitus：https://sploitus.com
## APP
+ 小蓝本：https://www.xiaolanben.com
+ 七麦：https://www.qimai.cn
+ AppStore：https://www.apple.com/app-store
## 公众号
+ 微信直接搜索
+ 搜狗：https://weixin.sogou.com
## 小程序
+ 微信直接搜索
# 信息深度收集：
## 指纹识别
+ 火狐插件：Wappalyzer
+ 云悉：http://www.yunsee.cn
+ whatweb：https://www.whatweb.net
+ 在线：http://whatweb.bugscaner.com/look (支持批量)
+ Nuclei：https://github.com/projectdiscovery/nuclei
## 目录扫描
+ Dirmap：https://github.com/H4ckForJob/dirmap
+ dirsearch：https://github.com/maurosoria/dirsearch
+ 7kbscan：https://github.com/7kbstorm/7kbscan-WebPathBrute
## JS接口
+ JSFinder：https://github.com/Threezh1/JSFinder
+ LinkFinder：https://github.com/GerbenJavado/LinkFinder
+ Packer-Fuzzer：https://github.com/rtcatc/Packer-Fuzzer (webpack)
+ 搜索关键接口
1. config/api
2. method:"get"
3. http.get("
4. method:"post"
5. http.post("
6. $.ajax
7. service.httppost
8. service.httpget
## WAF识别
+ WhatWaf：https://github.com/Ekultek/WhatWaf
+ wafw00f：https://github.com/EnableSecurity/wafw00f
