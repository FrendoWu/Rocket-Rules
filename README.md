# Rocket-Rules
Frendo 自用 ShadowRocket rules.
结合了[ConnersHua](https://github.com/ConnersHua/Profiles)、[Hackl0us](https://github.com/Hackl0us/SS-Rule-Snippet)以及[lhie1](https://github.com/lhie1/Rules)大神的规则。
删除了小火箭原生自带的绝大部分Reject规则，因为：

1. 这些垃圾网址的域名和IP更换频繁，难以永久屏蔽；
2. 针对Safari的广告屏蔽可以用ADguard，这样不开小火箭时也能获得广告屏蔽，何必多此一举；
3. 部分Reject规则可能导致访问出错。

最终规则内容包含如下：

* 本地路由等不走代理；
* Apple服务器的针对优化；
* 针对USER-AGENT进行整改App都走代理/不走代理优化；
* 百度、阿里、腾讯、网易、优酷、搜狐的部分广告屏蔽；
* Telegram特殊优化；
* 屏蔽flurry、doubleclick、金山、51la、umeng的统计；
* 国内常用网站直连、国外常用网站代理；
* 所有IP地址为CN的直连，剩下的代理；
* 开启MITM，并让google.cn自动跳转到google.com
