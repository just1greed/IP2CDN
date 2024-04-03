### IP->CDN验证方式



从cdn的原理出发，可供检测的有几个切入点：**txt** 、 **cname** 、   和   **CDNip**

可以通过ip反查url接口(自行实现) 或 PTR反查来得到域名，再通过域名拿到cname和txt

其中针对cname的项目或服务比较少    [全国主流CDN厂商cname域名汇总](https://github.com/u9sky/cdn-cname-domain)

针对txt可以关键词检测是否有cdn相关字段



#### 厂商公布的CDN ip段

cloudfront:
   - https://d7uri8nf7uskq.cloudfront.net/tools/list-cloudfront-ips

fastly:

   - https://api.fastly.com/public-ip-list

google:

   - https://www.gstatic.com/ipranges/goog.json

stackpath:

   - https://k3t9x2h3.map2.ssl.hwcdn.net/ipblocks.txt

CacheFly

- https://cachefly.cachefly.net/ips/cdn.txt

Cloudflare

- https://www.cloudflare.com/ips-v4

Incapsula

- https://my.incapsula.com/api/integration/v1/ips

MaxCDN

- https://support.maxcdn.com/hc/en-us/article_attachments/360051920551/maxcdn_ips.txt

Gcore

- https://api.gcore.com/cdn/public-ip-list

BunnyCDN

- https://api.bunny.net/system/edgeserverlist/plain

CDN77

- https://files.imunify360.com/static/whitelist/v2/cdn77.txt

Keycdn

- https://www.keycdn.com/shield-prefixes.json

quic.cloud

- https://quic.cloud/ips

Akaima

- https://techdocs.akamai.com/origin-ip-acl/docs/update-your-origin-server

百度云

- https://su.baidu.com/help/index.html#/10_changjianwenti/0_HIDE_FAQ/20_baiduyunjiasujiedianIPdizhiduan.md

阿里云

- https://help.aliyun.com/noticelist/articleid/6697641.html

CF CDN

- https://www.anancdn.com/ips.php

上海云盾CDN

- https://www.yundun.com/help.html#/cdn-ip

censys

- https://support.censys.io/hc/en-us/articles/360043177092-Opt-Out-of-Data-Collection



未验证：

- 腾讯云
- 加速乐
- 天御云SCDN





