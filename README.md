# My_Golang_path


javaScript
compile_path --js_out=import_style=commonjs,binary:. employees.proto

GO

 to use just rpc 

protoc --go_out=plugins=grpc:. --go_opt=paths=source_relative proto/\*.proto

!to use gprc 

protoc --proto_path=proto --proto_path=third_party --go_out=plugins=gprc:proto service.proto
protoc --go_out=plugins=grpc:. --go_opt=paths=source_relative proto/\*.proto

<!-- Notice -->

<!-- ?output the gprc file to the root directory -->

--go_opt=paths=source_relative

 Resources 

https://developers.google.com/protocol-buffers/docs/reference/go-generated
https://github.com/protocolbuffers/protobuf/releases
https://github.com/golang/protobuf
