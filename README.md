I'm using Python to grab live YouTube stats like likes, views, comments, and favorites using the YouTube Data API.
I set up Kafka to stream this data in real time. It's like having a virtual conveyor belt for my YouTube stats.
For crunching numbers and making sense of the data, I dive into KSqlDB. It's my go-to for real-time stream processing using SQL queries that feel like chatting with a database.
Once the data is processed and ready to rock, I fire it off to a Telegram bot, which then pushes out real-time notifications based on the processed YouTube metrics.
The entire project is containerised inside docker, so that it will work on any setup. 


Requirements

Python 3.10 (minimum)
Kafka
Telegram API
Docker
Confluent Containers (Zookeeper, Kafka, Schema Registry, Connect, ksqlDB, Control Center)
