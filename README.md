# go-microservices-example

Microservices implementation with Go, gRPC, Docker, PostgreSQL, and NSQ.

![alt text](microservices.svg)

## Generate Protobuf
```
cd proto
sh users-gen.sh
```

## Run
```
$ make run
```

## Ports
- App: `http://localhost:8080`
- Postgre Admin: `http://localhost:4171`
- NSQ Admin: `http://localhost:5050`