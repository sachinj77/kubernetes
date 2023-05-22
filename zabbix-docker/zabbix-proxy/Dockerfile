FROM zabbix/zabbix-proxy-sqlite3:ubuntu-5.0-latest

USER root
RUN apt-get -y update && apt-get -y install iputils-ping traceroute nmap snmp && rm -rf /var/lib/apt/lists/*
USER 1997
