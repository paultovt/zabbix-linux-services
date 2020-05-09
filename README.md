# Simple zabbix template for linux services monitoring

Allows you to monitor if services are disabled/down/failed.

# Instruction

1. Copy userparameter_services.conf to /etc/zabbix/zabbix_agentd.d/

2. Add services you want to monitor to /etc/zabbix/zabbix_agentd.d/userparameter_services.lst

3. Add Zabbix services template.xml to zabbix templates (once to zabbix server)

4. Add template "Services" to client machine's settings in zabbix

5. Wait an hour due to discovery update
