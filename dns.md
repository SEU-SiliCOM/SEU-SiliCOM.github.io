## 内网DNS服务

为改善校园内上网体验，社团在内网提供DNS服务，IP为`10.201.0.140`

本DNS从 [AliDNS](https://www.alidns.com/) [DNSPod](https://docs.dnspod.cn/public-dns/5fb5db1462110a2b153a77dd/) [IIJ](https://public.dns.iij.jp/) [DNS666](https://tuna.moe/help/dns/) 四个上游 DoT/DoH DNS服务器优选解析结果，使你拥有良好的CDN接入体验，并防止运营商污染解析记录。

DNS已启用[easylist](https://easylist.to/)与[I don't care about cookies](https://www.i-dont-care-about-cookies.eu/)规则，提供了基础的广告过滤功能。若有更激进的去广告需求，建议自行加装Ublock Origin, AdBlock Plus或其他去广告插件。

因IPv6网络建设不完备，且教育网路由普遍绕北京，cernet2与hkix的互联亦不稳定，本DNS **丢弃所有IPv6解析结果** 。需要注意的是，如果你打算使用(纯)ipv6刷PT，可能会因此无法解析tracker的ipv6位址，建议自行添加hosts条目。

我们建议将首选DNS服务器设为此地址，并 **另外配置至少一个DNS服务器** (如:119.29.29.29). 当前服务无在线率保证，若遇到问题请检查此页面是否更新，或[发电邮反馈](mailto:root@colder.one)。

## 效果展示

### GitHub

![rawgithubusercontent](https://i.loli.net/2021/03/18/Jvr2a37QK8mFAlP.jpg)

### steam聊天(好友网络、创意工坊等均类似)

这是我们的DNS解析结果，就近接入akamai日本节点（众多游戏平台均使用Akamai CDN）：  
![steam-chat](https://i.loli.net/2021/03/18/J7kVaZMPxRrT9Du.jpg)

而其他DNS服务器解析结果颇为随机，环游美西、绕美去德、绕美回港等情况往往使你的体验严重受损。  
![SEUWLAN默认DNS](https://i.loli.net/2021/03/18/cNJu2BfAhOsmP5I.jpg)

### Uplay

Uplay客户端更新是否让你痛不欲生？我们的DNS解析为您提供良好的接入：  
![Uplay](https://i.loli.net/2021/03/18/emXtSEAwo2gU94i.jpg)

### BiliBili

就算是国内网站我们也能让你就近接入。

我们为您优选上海节点：  
![shanghai](https://i.loli.net/2021/03/18/pYyOhSBDWcmTj5H.jpg)

不必远赴广州（对比校园网默认DNS）：  
![guangzhou](https://i.loli.net/2021/03/18/cErU7IlVG4NfqMz.jpg)