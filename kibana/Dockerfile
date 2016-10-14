FROM kibana:5

RUN sed -ri "s!^(\#\s*)?(server\.host:).*!\2 '0.0.0.0'!" /etc/kibana/kibana.yml \
    && grep -q '0.0.0.0' /etc/kibana/kibana.yml
