protoc:
	protoc --go_out=./grpc/proto --go-grpc_out=./grpc/proto  ./grpc/proto/user.proto

client:
	go run ./grpc/client/client.go

server:
	go run ./grpc/server/server.go

gorm:
	go run ./gin+gorm/main.go                            

redis:
	go run ./gin+redis/main.go