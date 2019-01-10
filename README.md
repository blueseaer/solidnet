# solidnet
Simple game server framework for Golang

详细设计文档，请参见：[《solidnet详细设计文档》](https://github.com/idakun/solidnet/wiki/Design-description-of-solidnet)

# install
go get github.com/idakun/solidnet

# examples

1. 进入examples目录
2. 执行make
3. 在bin目录下生成服务端和客户端程序

进入bin目录，启动程序测试：

1. 执行 ./server 127.0.0.1:8000  启动服务端
2. 执行 ./client 127.0.0.1:8000 200 启动客户端

examples的详细说明文档，请参见：[《examples设计说明》](https://github.com/idakun/solidnet/wiki/Design-description-of-examples)
