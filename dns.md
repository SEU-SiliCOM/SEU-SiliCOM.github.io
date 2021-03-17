## 内网DNS服务（试运行）

为改善校园内上网体验，社团在内网提供DNS服务，IP为`10.201.17.228`

本DNS从 AliDNS DNSPod 360 IIJ 四个上游 DoT DNS服务器优选解析结果，对联通/校园网(当前校园网出国流量走联通)线路十分友好。  
另外，考虑到ipv6网络建设尚未成熟，且教育网路由普遍绕北京，本DNS丢弃ipv6解析结果。

我们建议将首选DNS服务器设为此地址，并另外配置至少一个DNS服务器（如:119.29.29.29），当前服务无在线率保证，若遇到问题请及时在群内反馈。

## 效果展示

### GitHub

![rawgithubusercontent](https://i.loli.net/2021/03/18/H68pvi1gFL2JId9.png)

### steam聊天(好友网络、创意工坊等均类似)

这是我们的DNS解析结果，就近接入akamai日本节点（众多游戏平台均使用Akamai CDN）：  
![steam-chat](https://i.loli.net/2021/03/18/H68pvi1gFL2JId9.png)

而其他DNS服务器解析结果颇为随机，环游美西、绕美去德、绕美回港等情况往往使你的体验严重受损。  
![SEUWLAN默认DNS](https://i.loli.net/2021/03/18/cNJu2BfAhOsmP5I.jpg)

### Uplay

Uplay客户端更新是否让你痛不欲生？我们的DNS解析为您提供良好的接入：  
![Uplay](https://i.loli.net/2021/03/18/emXtSEAwo2gU94i.jpg)

### BiliBili

就算是国内网站我们也能让你就近接入。

我们为您优选出上海节点：
![shanghai](https://i.loli.net/2021/03/18/pYyOhSBDWcmTj5H.jpg)

不必远赴广州（对比校园网默认DNS）：
![guangzhou](https://i.loli.net/2021/03/18/cErU7IlVG4NfqMz.jpg)