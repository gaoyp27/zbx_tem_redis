# Multi Instance Redis Discovery Template for Zabbix 3.4
------
Zabbix server must be >= 3.4 And Tested on CentOS 6    
Put the 'userparameter_redis_lld_plus.conf' into $UserParameter's directory.    
On the zabbix server web page import XML template file.    
Need command: telnet redis-cli ss (Should have root privileges to list sockets with ss command)

> * Discovering redis instances and who is slave through ports
> * Get redis info/config/slaveinfo and output json format
> * Create "Dependent Item" by "preprocessing"
> * Generate graphs and Key indicators trigger
    
![Alt text](https://github.com/cuimingkun/zbx_tem_redis/blob/master/graphs.png)
