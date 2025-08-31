1- download kafkka 
  https://kafka.apache.org/download

2- run zookeeper server
    E:\Messaging\kafka\bin\windows\zookeeper-server-start.bat E:\Messaging\kafka\config\zookeeper.properties

3- run kafkka server
   E:\Messaging\kafka\bin\windows\kafka-server-start.bat E:\Messaging\kafka\config\server.properties

4- Creating topic
   E:\Messaging\kafka\bin\windows\kafka-topics.bat --create --bootstrap-server localhost:9092 --replication-factor 1 --partitions 1 --topic javatute-topic-1
    Created topic javatute-topic-1.
