# https://www.docker.elastic.co/
FROM docker.elastic.co/elasticsearch/elasticsearch:7.16.3-arm64

WORKDIR /usr/share/elasticsearch


# Add your elasticsearch plugins setup here
# Example: RUN elasticsearch-plugin install analysis-icu
RUN bin/elasticsearch-plugin install --batch analysis-nori
