
gin_demo2>go build src/main/main.go

#编译到bin下
gin_demo2\src\main>go install
一定要管理好目录
多个项目最好都在一个$GOPATH下面，即src/proj1，src/proj2，etc
尽量使用go install，这样能够规范项目整体结构