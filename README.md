## Getting up & running

#### Pre-Mantra : 

Try to understand what you're doing, and why. Really.

<img src="https://media.makeameme.org/created/one-does-not-5b913b.jpg" width="125"></img>

#### Prerequesites : 

- You are properly connected to your Linux instance (RHEL/Centos/Amazon Linux)

- Install Java

```
sudo yum install -y -q java-1.8.0-openjdk
```

#### Download the Kafka source

```
wget https://downloads.apache.org/kafka/2.5.0/kafka_2.12-2.5.0.tgz

tar -xzf kafka_2.12-2.5.0.tgz
cd kafka_2.12-2.5.0
```

#### Start a quick & dirty single-node Zookeeper instance
```
bin/zookeeper-server-start.sh config/zookeeper.properties >zk.log&
```

#### Start the Kafka Server
```
bin/kafka-server-start.sh config/server.properties >ks.log&
```

#### Check everything is ok

<img src="https://blog.iron.io/wp-content/uploads/2014/04/stay-paranoid-and-trust-no-one.png" width="80"></img>
```
  - ps command output : you should have 2 java processes
  - Lookup zk.log & ks.log : Make sure everything is fine
```


