# https://github.com/elastic/logstash-docker
FROM docker.elastic.co/logstash/logstash:5.2.1

# Example: RUN logstash-plugin install logstash-filter-json

RUN logstash-plugin install logstash-filter-useragent
RUN logstash-plugin install logstash-filter-range
