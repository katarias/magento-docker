FROM elasticsearch:7.11.1
LABEL maintainer="sahilkataria.1989@gmail.com"
# Magento 2 required plugins
RUN \
    elasticsearch-plugin install analysis-icu && \
    elasticsearch-plugin install analysis-phonetic
