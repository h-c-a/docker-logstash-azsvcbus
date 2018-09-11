# docker-logstash-azsvcbus
Logstash with Azure Service Bus input, and Gelf output.  
Usage:
```
ducker run --rm --name azure-service-bus-to-gelf \
 -v $PWD/example.config:/usr/share/logstash/pipeline/pipeline.conf \
 linkfire/logstash-azsvcbus-gelf
```
