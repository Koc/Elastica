FROM docker.elastic.co/elasticsearch/elasticsearch:6.0.0-rc2
MAINTAINER Nicolas Ruflin <spam@ruflin.com>

RUN /usr/share/elasticsearch/bin/elasticsearch-plugin install ingest-attachment


# Copy config files
COPY elasticsearch.yml /usr/share/elasticsearch/config/elasticsearch.yml
COPY scripts/* /usr/share/elasticsearch/config/scripts/
