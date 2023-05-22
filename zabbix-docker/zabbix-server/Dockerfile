FROM zabbix/zabbix-server-mysql:ubuntu-5.0-latest

USER root
RUN apt-get -y update && apt-get -y install snmp && rm -rf /var/lib/apt/lists/*
USER 1997
