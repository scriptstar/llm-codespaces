docker run -it \
 --rm \
 --name elasticsearch \
 -m 4GB \
 -p 9200:9200 \
 -p 9300:9300 \
 -e "discovery.type=single-node" \
 -e "xpack.security.enabled=false" \
 docker.elastic.co/elasticsearch/elasticsearch:9.0.3

> homework

docker run -it \
 --rm \
 --name elasticsearch \
 -m 4GB \
 -p 9200:9200 \
 -p 9300:9300 \
 -e "discovery.type=single-node" \
 -e "xpack.security.enabled=false" \
 docker.elastic.co/elasticsearch/elasticsearch:8.17.6

"build_hash" : "dbcbbbd0bc4924cfeb28929dc05d82d662c527b7"
