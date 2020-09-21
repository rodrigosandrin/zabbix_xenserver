# Zabbix Xenserver
This templates Monitoring Xenserver disks HBA and Memory from all nodes. 
The agent is setup on xenserver master.

## Install Zabbix Agent on Xenserver


## Configure template
* Create xenserver user with read-only role (tested with active directory user)
* Edit the file zabbix_agentd.d/xenserver/xen_passwd
* Import template on Zabbix server (tested on zabbix 4.4)
