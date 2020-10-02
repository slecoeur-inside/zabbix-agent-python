FROM zabbix/zabbix-agent:ubuntu-latest

USER 0

# Install python/pip
# Install python/pip
ENV PYTHONUNBUFFERED=1
RUN apt-get update && apt-get install -y python3 && ln -sf python3 /usr/bin/python
RUN chmod a+x /usr/bin/docker-entrypoint.sh

USER 1997