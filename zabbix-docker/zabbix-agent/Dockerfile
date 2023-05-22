FROM zabbix/zabbix-agent:ubuntu-5.0-latest

USER root
RUN apt-get -y update && apt-get -y install mariadb-client && rm -rf /var/lib/apt/lists/*
USER 1997
