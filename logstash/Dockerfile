# https://www.docker.elastic.co/
FROM docker.elastic.co/logstash/logstash:7.9.2

USER root
COPY logstash.conf /usr/share/logstash/logstash.conf
COPY logstash.yml /usr/share/logstash/config/logstash.yml

