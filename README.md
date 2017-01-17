# Surge.conf / Shadowrocket.conf

* 智能分流
* 屏蔽常用视频网站广告
* 屏蔽常用网站广告、其他流媒体网站广告
* 屏蔽部分应用程序开屏广告
* 屏蔽部分运营商劫持网页弹出的漂浮球广告
* 屏蔽部分运营商劫持网页弹出的流量统计
* 拦截常用应用程序的隐私跟踪
* 拦截常用应用程序的行为分析
* 拦截常用应用程序的数据统计
* 所有国内网站均直接连接
* 可突破部分内网限制（公司、学校）
* 解决本地 DNS 可能带来的干扰
* Apple 服务加速（App Store、Apple Music、Apple流媒体、iCloud备份、iCloud Drive、iTunes 等）
* 国外常用网站加速（Google/Youtube/Twitter/Facebook/instagram/wikipedia/Github 等）

♻️ Download：

    Surge：https://raw.githubusercontent.com/lhie1/Surge/master/Surge.conf
    
    Shadowrocket：https://raw.githubusercontent.com/lhie1/Surge/master/Shadowrocket.conf
    
    更新日志：https://raw.githubusercontent.com/lhie1/Surge/master/more/New

🆙 一键更新 for Surge （Workflow）：

    单节点版：https://workflow.is/workflows/7c3439f8ae2340d481dc16027eafa322

    多节点版：https://workflow.is/workflows/b42d7d3c6bcd443d951889d0deb4a803

# more

🔰 客户端（有“R”标示表示支持 SSR）：

    * iOS
    
        Surge：https://appsto.re/cn/D0Q_9.i
        
        Shadowrocket (R)：https://appsto.re/cn/UDjM3.i
        
        Wingy (R)：https://appsto.re/cn/19xBeb.i
        
        Potatso (R)：https://appsto.re/cn/OIk1_.i
        
    * Android
    
        ShadowsocksR (R)：https://github.com/shadowsocksr/shadowsocksr-android/releases
        
        Postern (R)：http://www.tunnel-workshop.com
        
    * macOS
    
        ShadowsocksX：https://github.com/shadowsocks/shadowsocks-iOS/releases

        ShadowsocksX-R (R)：https://github.com/yichengchen/ShadowsocksX-R/releases

        ShadowsocksX-NG (R)：https://github.com/qinyuhang/ShadowsocksX-NG/releases
        
        Flora：https://github.com/huacnlee/flora-kit

        Specht Lite：https://github.com/zhuhaow/SpechtLite/releases
        
        Surge：http://nssurge.com
        
    * Windows
    
        ShadowsocksR (R)：https://github.com/shadowsocksr/shadowsocksr-csharp/releases
        

📋 教程 / 说明：

    Surge for iOS：http://t.cn/RUfiwq0
    
    Surge for macOS：http://t.cn/RIQs6O7
    
    Shadowrocket：http://t.cn/RqKIk3Z

    Specht Lite for macOS：http://t.cn/RMvOpm5
    

# line

*** | Raw |
---------|:---------:
LHIE1| [翻墙服务](https://item.taobao.com/item.htm?spm=686.1000925.0.0.nxFmSh&id=524385498809)
新浪微博 | [ @lhie1](http://www.weibo.com/1748625493)
Telegram | https://telegram.me/lhie1x


# 帮助到您？捐赠鼓励！

![](/img/alipay.png "alipay：lhie1@qq.com")     ![](/img/WeChat.png "WeChat：lhie1x")

# Q&A

### ☁️ Proxy & 🔰 Proxy & 🍎 Proxy / # Auto Test Group

    ☁️ Proxy ： 直连 / 代理服务器(选择 [🌍 Direct] 为 直连，选择 [其他] 则通过 代理服务器 访问)

    🔰 Proxy ： 自动代理 / 全局代理(选择 [🌍 Direct] 为 智能分流 (Pac) ，选择 [☁️ Proxy] 即为 全局代理 )

    🍎 Proxy ： 如果连接苹果服务器困难， [🍎 Proxy] 选 代理服务器 ，可能会改善一些问题。

    如果 ： [☁️ Proxy] 、 [🔰 Proxy] 都选择 代理服务器 ，则为全局代理（不包括 [🍎 Proxy]）。

    🏃 Auto ： 对规则内的所有服务器进行“测速”，并根据最优结果自动选择节点。

    🍎 Auto ： 对规则内的所有服务器进行“测速”，并根据最优结果自动选择节点。（针对 [🍎 Proxy] 所设计的分组）


    建议 ：☁️ Proxy - 代理服务器 、 🔰 Proxy - 🌍 Direct 、 🍎 Proxy - 🌍 Direct /  🍎 Auto



#### 🚀 SSR 混淆模式 https://github.com/breakwa11/shadowsocks-rss/blob/master/ssr.md

    理论上开启混淆模式可以更好的躲开墙的干扰以及非正常流量的限速，那就应当会获得更好的速度和稳定性。



#### 🔋 Surge for iOS 耗电

    Surge 会接管全局的（几乎）所有通信，所以所有的网络方面电量消耗都会被算在 Surge 头上，实际使用中不会感到 Surge 对电量有明显影响。



#### ☑️ Set as System Proxy

    启用 Surge for Mac 后勾选下拉菜单中的 Set as System Proxy 即可自动向系统网络设置添加必要的参数，因为需要修改系统网络设置，首次勾选时需要输入管理员密码进行确认，去掉 Set as System Proxy 的勾选，会清除网络设置中的代理相关设置。



#### 📶 Surge for iOS 开启共享模式 https://medium.com/@scomper/局域网其他设备共享上网-dd29e18853da#.6w19tdsh9

    Surge 在增加了代理共享模式，只需要开启就能让 Wi-Fi 网络中的其他设备通过这台 iPhone 代理访问网络。
    到高级设置中开启 Allow Wi-Fi Access ，或者直接修改配置文件，添加一行参数 allow-wifi-access = true。

    其他 Wi-Fi 网络环境下的设备可以输入已经开启共享代理的 Surge 设备的 IP 地址和端口号，（技巧：Surge Log 中能看到开启后本机的 IP 地址和监听端口）将 IP 地址填写到需要共享设备的 Wi-Fi 信息的 HTTP 代理里即可。



#### 🏃 Auto / Benchmarik

    测试结果仅供参考，无法检测出 VPS 的带宽

    请不要使用 google.com 作为测试目标，有可能导致 proxy 服务器 ip 被加入黑名单，导致各种操作需要输入验证码。
    目标 URL 对所有的 policy 是基本公平的，所以请选择像 gstatic.com 这样的在全球都有节点的 URL 作为测试目标。
    作者建议：http://www.gstatic.com/generate_204



#### 🍎 Apple DNS （Apple 服务加速） http://t.cn/RcgOudi

    Apple DNS 通过收集 Apple 在全中国几乎所有省级行政区的 CDN IP 列表，解决 App Store / Mac App Store / iTunes Store / Apple Music / iBooks / TestFlight 在中国部分地区速度缓慢的问题。

    ChinaNet：电信宽带专用
    ChinaUnicom：联通宽带专用
    auto(原 CMCC)：电信、联通、移动 三网通用

    电信、联通宽带用户可以自行按照教程生成最适合自身网络环境的 CDN IP 列表，移动宽带用户或嫌麻烦的用户使用 auto 列表即可。

    Apple DNS参考：

    [Host]
    // Apple DNS

    // China Net (中国电信)
    # API-1-ChinaNetCenter [ChinaNet] (Avg RTT: 9.772ms)
    se.itunes.apple.com = 222.211.64.122
    su.itunes.apple.com = 222.211.64.122
    upp.itunes.apple.com = 222.211.64.122
    play.itunes.apple.com = 222.211.64.122
    client-api.itunes.apple.com = 222.211.64.122
    # API-2-ChinaCache [ChinaNet] (Avg RTT: 15.339ms)
    itunes.apple.com = 125.65.247.14
    init.itunes.apple.com = 125.65.247.14
    # API-HK-Akamai-1 [HongKong0] (Avg RTT: 52.706ms)
    search.itunes.apple.com = 184.87.97.50
    # API-HK-Akamai-2-AMRadio [HongKong1] (Avg RTT: 58.221ms)
    radio.itunes.apple.com = 184.87.100.246
    radio-activity.itunes.apple.com = 184.87.100.246
    radio-services.itunes.apple.com = 184.87.100.246
    # Apple Music Streaming [ChinaNet-ChinaCache] (Avg RTT: 10.465ms)
    aod.itunes.apple.com = 139.206.198.9
    mvod.itunes.apple.com = 139.206.198.9
    streamingaudio.itunes.apple.com = 139.206.198.9
    # Beats 1 Radio (Not Available in Mainland China) [Malaysia] (Avg RTT: 90.211ms)
    itsliveradio.apple.com = 202.76.239.11

    // China Unicom （中国联通）
    # API-1-ChinaNetCenter [ChinaUnicom] (Avg RTT: 71.482ms)
    se.itunes.apple.com = 123.138.61.6
    su.itunes.apple.com = 123.138.61.6
    upp.itunes.apple.com = 123.138.61.6
    play.itunes.apple.com = 123.138.61.6
    client-api.itunes.apple.com = 123.138.61.6
    # API-2-ChinaCache [ChinaUnicom] (Avg RTT: 62.808ms)
    itunes.apple.com = 60.6.197.202
    init.itunes.apple.com = 60.6.197.202
    # API-HK-Akamai-1 [HongKong0] (Avg RTT: 109.218ms)
    search.itunes.apple.com = 23.42.189.88
    # API-HK-Akamai-2-AMRadio [HongKong1] (Avg RTT: 192.861ms)
    radio.itunes.apple.com = 23.13.185.169
    radio-activity.itunes.apple.com = 23.13.185.169
    radio-services.itunes.apple.com = 23.13.185.169
    # Apple Music Streaming [ChinaUnicom-ChinaNetCenter] (Avg RTT: 27.633ms)
    aod.itunes.apple.com = 113.207.6.58
    mvod.itunes.apple.com = 113.207.6.58
    streamingaudio.itunes.apple.com = 113.207.6.58
    # Beats 1 Radio (Not Available in Mainland China) [Malaysia] (Avg RTT: 90.211ms)
    itsliveradio.apple.com = 202.76.239.11

    // Auto （三网通用）
    aod.itunes.apple.com = hkg.aapldns.xyz
    streamingaudio.itunes.apple.com = hkg.aapldns.xyz
    aodp.itunes.apple.com = hkg.aapldns.xyz
    iosapps.itunes.apple.com = hkg.aapldns.xyz
    osxapps.itunes.apple.com = hkg.aapldns.xyz
    swcdn.apple.com = hkg.aapldns.xyz
    appldnld.apple.com = hkg.aapldns.xyz
    itsliveradio.apple.com = 42.99.128.168
    // aapldns.xyz 由 AppleDNS Team 托管，以 CNAME 的方式解析 Apple 服务器 IP


# License

* 可以拷贝、转发，但是必须提供原作者信息，同时也不能将本项目用于商业用途。
