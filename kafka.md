### JSON to Topic

`jq -rc . /Users/d071598/Documents/Dev/tmp/kafka/clickstream.json | bin/kafka-console-producer.sh --topic slim --bootstrap-server localhost:9092`
