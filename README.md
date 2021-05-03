# grpc-playground-proto

Protocol buffer files repository for the playground services. Each one of these proto files is the source of truth for a
gRPC service definition.

## Assets generation
- [Protobuf Gradle Plugin](https://github.com/google/protobuf-gradle-plugin)
- Run generate jar: `./gradlew clean jar`. 
- Target location is `build/libs/grpc-playground-proto.jar`
