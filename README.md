# kafka-consumer-wikimedia
this service fetches wikimedia data that written to the topic by the [kafka-producer-wikimedia](https://github.com/kutayyaman/kafka-producer-wikimedia) service.
If you want to try this project you must set up a `kafka` server on port `9092` and you must up this project [kafka-producer-wikimedia](https://github.com/kutayyaman/kafka-producer-wikimedia). You must
up this producer project because it feeds the topic this project is listening to. After you up a kafka server on port 9092 and up kafka-producer-wikimedia project you can run this application and see wikimedia logs.
