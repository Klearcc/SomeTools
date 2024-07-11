# SomeTools
Some tools that are not easy to find

### crackmapexec v6.0.1 for arm linux
https://github.com/Klearcc/SomeTools/blob/main/crackmapexec-3_v6.0.1.r198.gda472cb-1-any.pkg.tar.zst
```bash
> cd crackmapexec-3_v6.0.1.r198.gda472cb-1-any.pkg && cp -r ./usr/share/crackmapexec /usr/share && cp ./usr/bin/* /usr/bin

> cd /usr/share/crackmapexec && poetry install

use:
> cme or crackmapexec
```
### netexec v1.1.0 for arm linux
https://github.com/Klearcc/SomeTools/blob/main/netexec-v1.1.0.r8.ga6be6c1b-1-any.pkg.tar.zst
```bash
> cd netexec-v1.1.0.r8.ga6be6c1b-1-any.pkg && cp -r ./usr/share/netexec /usr/share/ && cp ./usr/bin/* /usr/bin

> cd /usr/share/netexec && poetry install

use:
> nxc or netexec
```
### proxy_server
基于https://github.com/avplayer/proxy  
```
##做服务端
### http服务
./proxy_server_linux_amd64 --disable_logs true --http_doc .  --auth_users "" --autoindex true --server_listen [::0]:1080
### 代理。http&socks通用
./proxy_server_linux_amd64   --auth_users "user:pass" --disable_logs true --disable_insecure false --server_listen 0.0.0.0:1080

##做客户端
### 启动后会在本地启socks&http1080
./proxy_server_linux_amd64 --auth_users "" --disable_logs true  --disable_insecure false  --proxy_pass socks5://user:pass@ip:port
```

### ios脱壳app，文件太大无法上传至github，需要请留言
```
Discord_181.0增强版自带翻译功能tg巨魔商店.ipa
Nicegram1.4.6破解会员.ipa
抖音_23.2.1_港版+净化_秋名山.ipa
TikTok_30.3.0_免拔卡破解BHTiktok汉化tg巨魔商店.ipa
Twitter_9.56_BHT391_com.atebits.Tweetie2.ipa
YouTube_18.29.1_uYou_3.0.1.ipa
微信_8.0.44.ipa
直播聚合simple-live.ipa
Reeder 5 (5.4).ipa
```

### wechat插件
```
PKC_0.4-4.deb
sutuplus_5.7.3-1.deb
uYou.dylib           
微信净化2.23.dylib
黄白助手1.6.5.deb
```
