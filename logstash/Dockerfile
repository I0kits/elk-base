# https://github.com/elastic/logstash-docker
FROM docker.elastic.co/logstash/logstash:5.2.2

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json

HEALTHCHECK CMD curl -Ifs http://localhost:9600 || exit 1
