# wafid - A Wonderful Tool

 WAFid - Web Application Firewall identify Tool

 Wafid allows one to identify and fingerprint Web Application Firewall (WAF) products protecting a website.
 
# Working of wafid
 Wafid sends a normal HTTP request and analyses the response; this identifies a number of WAF solutions.If that is not successful, it  sends a number of (potentially malicious) HTTP requests and uses simple logic to deduce which WAF it is If that is also not successful, it analyses the responses previously returned and uses another simple algorithm to guess if a WAF or security solution is actively responding to our attacks
 
 For further details, check out the source code on the main site, github.com/Cryin/wafid.
 
# Detection by wafid
 It detects a number of WAFs. 

 ``` 
python wafid.py -l
  
  __      __  _____  ___________.__    .___
/  \    /  \/  _  \ \_   _____/|__| __| _/
\   \/\/   /  /_\  \ |    __)  |  |/ __ | 
 \        /    |    \|     \   |  / /_/ | 
  \__/\  /\____|__  /\___  /   |__\____ | 
       \/         \/     \/            \/

WAFid - Web Application Firewall identify Tool
By Cryin'

WAFid can identify these WAFs:
  360
  Safedog
  NetContinuum
  Anquanbao
  Baidu Yunjiasu
  Knownsec KS-WAF
  BIG-IP
  Barracuda
  BinarySEC
  BlockDos
  Cisco ACE
  CloudFlare
  NetScaler
  FortiWeb
  jiasule
  Newdefend
  Palo Alto
  Safe3WAF
  Profense
  West263CDN
  WebKnight
  Wallarm
  USP Secure Entry Server
  Sucuri WAF
  Radware AppWall
  PowerCDN
  Naxsi
  Mission Control Application Shield
  IBM WebSphere DataPower
  Edgecast
  Applicure dotDefender
  Comodo WAF
  ChinaCache-CDN
  NSFocus
 ``` 

 Also you can add waf id with finger.xml!
 
# How do I use it?

 Usage: python wafid.py -u URL
 
# Thanks

[shellc0der](https://github.com/she11c0der)
 
# Questions?

 contact [me](416049355@qq.com)
 
 
