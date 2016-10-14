FROM logstash:5

COPY config/ /logstash/config/

CMD ["logstash", "-f", "/logstash/config/hello-world.conf"]
