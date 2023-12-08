test avec abs

Installation JAVA
Commande:
sudo apt-get update
sudo apt-get install openjdk-8-jdk-headless -qq

Kafka : 
Commande: wget https://archive.apache.org/dist/kafka/2.6.0/kafka_2.12-2.6.0.tgz 
Explication: Télécharge la distribution d'Apache Kafka depuis le site officiel.

Kafka : 
Commande: tar -xzf kafka_2.12-2.6.0.tgz
Explication: Décompresse l'archive Kafka téléchargée.


1. Démarrage de Zookeeper
./kafka_2.12-2.6.0/bin/zookeeper-server-start.sh ./kafka_2.12-2.6.0/config/zookeeper.properties

2. Démarrage du serveur Kafka
./kafka_2.12-2.6.0/bin/kafka-server-start.sh ./kafka_2.12-2.6.0/config/server.properties

3. Pour lancer un script appélé "producer.py" sur python sur un terminal
python producer.py

