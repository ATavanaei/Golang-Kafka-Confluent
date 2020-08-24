# Confluent's Golang Client for Apache KafkaTM
confluent-kafka-go is Confluent's Golang client for Apache Kafka and the Confluent Platform.

Features:

High performance - confluent-kafka-go is a lightweight wrapper around librdkafka, a finely tuned C client.

Reliability - There are a lot of details to get right when writing an Apache Kafka client. We get them right in one place (librdkafka) and leverage this work across all of our clients (also confluent-kafka-python and confluent-kafka-dotnet).

Supported - Commercial support is offered by Confluent.

Future proof - Confluent, founded by the creators of Kafka, is building a streaming platform with Apache Kafka at its core. It's high priority for us that client features keep pace with core Apache Kafka and components of the Confluent Platform.
connection produce an consume in kafka

Getting Started

Import the kafka package from GitHub in your code:

import "github.com/confluentinc/confluent-kafka-go/kafka"
