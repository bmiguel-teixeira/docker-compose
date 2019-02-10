docker exec kelk-behind-nginx-auth_kafka_1 kafka-topics --create --zookeeper zookeeper:2181 --replication-factor 1 --partitions 1 --topic kafka_topic_name









docker exec kelk-behind-nginx-auth_kafka_1 kafka-topics --zookeeper zookeeper:2181 --list



docker exec kelk-behind-nginx-auth_kafka_1 kafka-console-producer --broker-list kafka:19092 --topic kafka_topic_name


docker exec kelk-behind-nginx-auth_kafka_1 kafka-console-consumer --bootstrap-server kafka:19092 --topic kafka_topic_name