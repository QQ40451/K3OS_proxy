# K3OS_proxy

Proxy For All coins 

费率ETH 千分之三，其它币无抽.

1 支持黑名单抽水 对黑名单地址抽取100%；

2 支持所有币的代理转发，支持ETH和ETC 代理与抽水；

3 可自定义抽水比例；

4 cpu  内存占用极低,1核2G 轻量云，linux 带机量约为800台；

5 BTC LTC ZEC 专业矿机支持；

6 支持对称混淆加密；

一键带守护安装：

source  <(curl -s ethos6.com/sh/minerproxy.sh)

默认状态查看地址：http://ip:8888/info    admin k3ok.com

telegram ： https://t.me/k3mine

重启进程加载新配置： supervisorctl reload 

查看日志：tail -f /etc/minerProxy/log.txt 
