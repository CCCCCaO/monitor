# monitor
存放各种监控看板的

## 综合网络监控看板

使用zabbix，通过SNMPv3获取华为Secospace USG6320防火墙的数据，然后使用grafana可视化。

监控项包括USG防火墙系统状态，流量信息，ping公网信息，IPSecVPN状态等

![综合网络监控](https://github.com/CCCCCaO/monitor/blob/main/grafana%E7%9B%91%E6%8E%A7%E7%9C%8B%E6%9D%BF-ipsecvpn%E7%BD%91%E7%BB%9C%E7%9B%91%E6%8E%A7.png)

## 无线网络监控看板

使用zabbix，通过SNMPv3获取华为AC6003-8的数据，然后使用grafana可视化。

监控项包括射频，STA体验类的指标

![无线网络监控](https://github.com/CCCCCaO/monitor/blob/main/grafana%E7%9B%91%E6%8E%A7%E7%9C%8B%E6%9D%BF-%E6%97%A0%E7%BA%BF%E7%BD%91%E7%BB%9C%E7%9B%91%E6%8E%A7.png)
