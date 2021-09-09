```shell
./protoc/protoc-3.17.3-osx-x86_64/bin/protoc \
--plugin=protoc-gen-grpc-java=./protoc/protoc-gen-grpc-java/protoc-gen-grpc-java-1.20.0-osx-x86_64.exe \
--proto_path=./puppet/src/main/proto --grpc-java_out=./puppet/src/main/java/service ./puppet/src/main/proto/go_robot.proto

./protoc/protoc-3.17.3-osx-x86_64/bin/protoc \
--proto_path=./puppet/src/main/proto --java_out=./puppet/src/main/java/service ./puppet/src/main/proto/go_robot.proto
```