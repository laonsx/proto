# proto
grpc-gateway <br><br>
依赖:<br>
go get -u google.golang.org/grpc<br>
go get -u github.com/golang/protobuf/protoc-gen-go<br>
go get -u github.com/grpc-ecosystem/grpc-gateway/protoc-gen-grpc-gateway<br>
go get -u github.com/grpc-ecosystem/grpc-gateway/protoc-gen-swagger<br><br>
命令:<br>
protoc --go_out=plugins=grpc:./ *.proto<br>
protoc --grpc-gateway_out=./ *.proto<br>
protoc --swagger_out=./ *.proto<br>
