 FROM zabbix/zabbix-agent:ubuntu-latest

USER 0

# Install python/pip
# Install python/pip
ENV PYTHONUNBUFFERED=1
RUN apt install -y python3-pip && ln -sf python3 /usr/bin/python
RUN python3 -m ensurepip
RUN pip3 install --no-cache --upgrade pip setuptools

USER 1997