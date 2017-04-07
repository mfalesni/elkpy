FROM docker.elastic.co/logstash/logstash:5.3.0

ADD 01-python-logstash.conf /usr/share/logstash/01-python-logstash.conf

EXPOSE 5005
EXPOSE 5006

CMD ["-f", "/usr/share/logstash/01-python-logstash.conf"]