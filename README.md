# activator-kafka-java-producer-consumer

This activator project proves insights about how to read &amp; write data from kafka queue.

##Steps to Install and Run zookeeper and kafka on your system : 

Step 1: Download kafka

    http://kafka.apache.org/downloads.html

Step2: Extract it

    $ tar -xzf kafka_2.11-0.10.0.0.tgz
    $ cd  kafka_2.11-0.10.0.0

Step3: Start the server

Start  zookeeper:

     $ bin/zookeeper-server-start.sh config/zookeeper.properties

Start  Kafka server:

    $ bin/kafka-server-start.sh config/server.properties


##Steps to start producer service :

    ./activator "run-main com.knoldus.demo.ProducerApp"
  
##Steps to start consumer service :

    ./activator "run-main com.knoldus.demo.ConsumerApp"
  
