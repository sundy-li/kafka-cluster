# kafka-cluster
docker kafka-cluster

## docker-hub
	https://hub.docker.com/r/sundyli/kafka-cluster/

## usage
	- dataDir: /data/db/

## example
```
docker run --net host --name kafka \
	-p 9200:9200 \
	-v /data/db/kafka:/data/db/ \
	-d sundyli/kafka-cluster  ${id} lp2,lp3,lp4 
```