# Cassandra-Springboot

using docker 
obtaining latest cassandra image

´´´
 docker pull cassandra
´´´
running casandra image and binding container ports with machine ports

´´´
docker run --name cassandra -p 127.0.0.1:9042:9042 -p 127.0.0.1:9160:9160   -d 
cassandra
´´´