# Scala 2.13 / Java 17 Akka HTTP Streams gRPC example

This project is based on the official [akka-grpc-quickstart-scala](https://developer.lightbend.com/guides/akka-grpc-quickstart-scala/) guide and the [official akka grpc sample on github](https://github.com/akka/akka-grpc-sample-kubernetes-scala).

Uses only:
- Sbt
- Akka HTTP
- Akka streams

Download the above mentioned Akka gRPC quickstart for SSL support (local).

### Compile
```
./sbt compile
```

### Run the server
```
./sbt "runMain com.example.helloworld.GreeterServer"
```

### Run the client
```
./sbt "runMain com.example.helloworld.GreeterClient"
```