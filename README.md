# CIGAM: Indexação de logs da aplicação

## Logstash

-   [Logstash 7.8](https://artifacts.elastic.co/downloads/logstash/logstash-7.8.0.tar.gz)

## Execução

```
logstash -f pipelines/cigam.conf --pipeline.ordered=true --pipeline.workers=1
```
