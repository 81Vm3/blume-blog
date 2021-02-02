---
layout: post
title: "觅云 - 一家好用且高速的SSR/V2R机场"
author: "Blume"
tags: 翻墙
intro: "无惧晚间流量高峰，享受网上自由冲浪"
---

## 前言
由于长城防火墙导致的网络限制，需要采用一些科学上网手段，SSR是你的best friend

我曾经租过私人的VPS来搭建VPN服务器，可是效果却不是很理想，速度慢，需管理，费用高，最蛋疼的是只有一个IP :C  
当我发现有一家机场可以一劳永逸时，"我giao，还有这么方便的platfrom?"

## 觅云
觅云(MeCloud)是一家做中高端BGP隧道中转/IPLC内网专线的SSR/V2Ray机场，近3年的老牌子，一直比较低调。
觅云机场拥有CN2 GIA/阿里云CEN/PCCW/AWS/Azure/GCP/IPLC等顶级线路近80条，其中全部为BGP/CN2隧道中继和IPLC内网专线，IPLC专线根本就不经过GFW。
经过很长时间的使用，非常稳定，速度也很快，比大多数同类服务更稳定，可以作为主力用来科学上网、游戏加速等服务使用。

[**点我前往觅云官方网址**](https://www.miyun.fun/register?code=ouSHVmaT8ahCVCVt5wiljxQ7UbbdUa4v)

[**点我前往觅云官方网址**](https://www.miyun.fun/register?code=ouSHVmaT8ahCVCVt5wiljxQ7UbbdUa4v)

[**点我前往觅云官方网址**](https://www.miyun.fun/register?code=ouSHVmaT8ahCVCVt5wiljxQ7UbbdUa4v)

## 优势
- 线路全部采用BGP隧道中转和IPLC内网专线节点，所有节点均为无合租独服节点
- BGP中转线路采用WG隧道+GOST路由直连双重隧道加密
- 高级订阅功能，可以按媒体、专线或地区进行选择订阅链接
- 全平台支持 Windows/Mac/Android/iOS/Linux
- BGP中继独服服务器，主线入口为1G带宽，500M带宽的冗余CN2线路 ，北京200M联通，上海电信100M均可以轻松跑满
- 拥有香港、美国、东京、中国台湾等地区节点
- 支持4K/8K视频秒开，晚高峰也可以跑满带宽（需要你硬件支持）

## 价格
<img src="/assets/images/miyun-vip1.png" alt="drawing" style="max-width: 100%;"/>
<img src="/assets/images/miyun-vip2.png" alt="drawing" style="max-width: 100%;"/>

对于一般人的需求来说，100M速率+100GB流量已经很够了，流量每30天重置一次，未使用的流量不结转到下个周期。
你可以看看在Vultr上面搭的$5私人VPN，和觅云上买的20RMB的SSR/V2R，明显是觅云更划算一些。
注意关注领券中心！觅云时不时会发放福利 <3

注意事项：**只有专线套餐支持UDP协议、KCP加速和网络游戏加速功能**，而中继套餐不支持，但仍可用于游戏加速，效果相比于专线套餐要逊色很多。

## 常见问题
1. SSR觅云怎么样？觅云机场怎么样？
    * 非常优秀的一家老牌SSR/V2Ray机场，全部BGP隧道中转/IPLC内网专线，极速稳定，值得信赖
2. 觅云的官网在哪里?
    * [**点我前往觅云官方网址**](https://www.miyun.fun/register?code=ouSHVmaT8ahCVCVt5wiljxQ7UbbdUa4v)
3. 如何下载客户端?
    * 觅云是SSR/V2R机场，你使用通用的SSR客户端或V2Ray客户端就行，觅云官网提供客户端下载
    * 唯一值得注意的是Linux的客户端，觅云上提供的是 _Clash_，当然你也可以用别的SSR客户端比如 _Shadowsocks-Qt_
4. 为什么SSR客户端有时"无效"?
    * 客户端有代理规则，这决定了是否要对个别站点进行代理
    * SSR使用socks5协议，**画重点! 不是 VPN!!! 它没有虚拟网卡!!**如果想实现真正的"全局代理"，我推荐你用 _proxychains_，proxychains的使用方法在此不细讲
    * 有些游戏不支持代理，你可能需要 _SSTap_