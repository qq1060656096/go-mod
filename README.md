# go-mod
go mod示例模块

```sh
1. 在github创建一个仓库hellomod
2. 在GOPATH之外创建模块
3. 提交代码到github上

# 注意,代码必须推到仓库上, 其他人才能通过go get github.com/qq1060656096/hellomod 来使用这个包

# 在GOPATH之外创建模块
$ go mod init github.com/qq1060656096/hellomod
go: creating new go.mod: module github.com/qq1060656096/hellomod

# 提交代码到github
git add .
git commit -m 'aaa: go hello模块第一次提交'
git push origin master

```