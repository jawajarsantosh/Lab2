Lab2 - Grpc
=========
To build grpc:
```
$ ./gradlew install
```

Running the client:

$ ./gradlew :grpc-examples:pollServiceClient

Running the Server:

$ ./gradlew :grpc-examples:pollServiceServer

Client's Otput: Returns new Poll Id generated as the response.

Server's Output: Listen's to port 50051. Print's Moderator Id to stdout.