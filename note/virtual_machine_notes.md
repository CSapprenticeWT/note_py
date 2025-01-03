# virtual_machine_notes





## 1. 在 VMware 17Pro 上安装win7虚拟机

​	在[MSDN原站](https://msdn.itellyou.cn/)或[新站](https://next.itellyou.cn/)找到`win7`镜像。

​	一直下一步安装，密钥在网上搜一个，win7的很多。

​	主要记录几个问题：

1. 网络问题，在虚拟机设置中的网络适配器选项中选择NAT模式，勾选启动连接。然后启动虚拟机测试能否ping通宿主机。
   - 设置代理，如果宿主机使用了代理，可以在虚拟机中填写外部代理的转发端口号。**控制面板** ->**网络和Internet** -> **网络和共享中心** -> **Internet选项** -> **连接** -> **局域网设置** -> **代理服务器**中填写宿主机IP和使用的端口号。
2. 安装`VMWare Tools`



