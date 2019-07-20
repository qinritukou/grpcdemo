# grpcdemo

a simple go demo for create grpc api

# the command used
protoc --proto_path=proto --proto_path=third_party --go_out=plugins=grpc:proto service.proto

go get -u google.golang.org/grpc

go get -u github.com/golang/protobuf/protoc-gen-go


# ogirinal youtube video
https://www.youtube.com/watch?v=Y92WWaZJl24
