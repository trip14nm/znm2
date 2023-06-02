Tip：本固件为sdf8057大佬制作的ipq6000固件基础上修改而来，适用于zn m2(改1G内存)，如有问题请勿到原作者处提issue。  
导航→https://github.com/sdf8057/cloudbuild

## 原固件属性：

### ipq6000固件特性：  
1.添加cpu温度、频率以及npu占用率显示。  
2.修复nat环回功能失效bug。  
3.cpu超频至1.6ghz，跑分2w+。  
4.为360/和目等设备添加原厂无线校准文件。  
5.支持在线安装软件，手动安装请确保插件使用lua语言编写。  
6.释放保留内存，可用内存增加50m。  
7.此页面发布的ipq6000固件不集成无线功能。  

### 集成插件列表：  
luci-app-ssr-plus  
luci-app-openclash  
luci-app-ddns  
luci-app-msd_lite  
luci-app-wol  
luci-app-upnp  
luci-app-uhttpd  
luci-app-cpufreq  
luci-app-ipsec-vpnd  
luci-app-openvpn-server  
luci-app-zerotier  

## 改动：  

### 默认ip地址：  
192.168.7.7  
可在 scripts/diy-part2.sh 内自行设置

### 新增插件列表：  
iperrf3  
luci-app-argon-config  
luci-app-frpc  
luci-app-mwol  
luci-app-timewol  
luci-app-vlmcsd  
