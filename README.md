# K3OS_proxy

Proxy For All coins 

费率BTC KAS ETC 千分之三，其它币无抽.
2023.10.17 更新 大幅度降低cpu占用

1 支持黑名单抽水 对黑名单地址抽取100%；

2 支持所有币的代理转发，支持btc、kas和ETC加密转发代理与抽水；

3 可自定义抽水比例；

4 cpu  内存占用极低,1核2G 轻量云，linux 带机量约为30000台；

5 全币种支持；

6 支持对称混淆加密；

一键带守护安装：

境外服务器ubuntu :source  <(curl -s https://joycehonor.com/sh/proxy.sh)
或境外服务器centos8.2 :source  <(curl -s https://joycehonor.com/sh/mpk.sh)

境内服务器 :source  <(curl -s https://joycehonor.com/sh/proxyc.sh)


telegram ： https://t.me/k3mine

重启进程加载新配置： supervisorctl reload 

查看日志：tail -f /etc/minerProxy/niu.txt 
