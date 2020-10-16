# kafka-connect-postman-collection
A Postman collection for [Kafka Connect Rest API](https://docs.confluent.io/current/connect/references/restapi.html)

# Use of the collection
1. install [Postman](https://www.postman.com/)
2. clone the repository
3. open Postman
4. import the collection file Kafka Connect.postman_collection.json
5. import the environment file Kafka Connect Env.postman_environment.json
6. set the values for environment variables: 
 * KAFKA_CONNECT_ENDPOINT : endpoint of kafka connect (without http) 
 * KAFKA_CONNECT_CONNECTOR : name of a connector 
