FROM zabbix/zabbix-agent:ubuntu-latest

USER 0

# Install python/pip
# Install python/pip
ENV PYTHONUNBUFFERED=1
RUN apt-get update && apt-get install -y python2 && ln -sf python2 /usr/bin/python
RUN chmod 755 /usr/bin/docker-entrypoint.sh

USER 1997