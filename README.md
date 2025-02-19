[![API Reference](
https://camo.githubusercontent.com/915b7be44ada53c290eb157634330494ebe3e30a/68747470733a2f2f676f646f632e6f72672f6769746875622e636f6d2f676f6c616e672f6764646f3f7374617475732e737667
)](https://godoc.org/github.com/33cn/chain33)
[![pipeline status](https://github.com/33cn/chain33/actions/workflows/build.yml/badge.svg)](https://github.com/33cn/chain33/actions/)
[![Go Report Card](https://goreportcard.com/badge/github.com/33cn/chain33)](https://goreportcard.com/report/github.com/33cn/chain33)
 [![Windows Build Status](https://ci.appveyor.com/api/projects/status/github/33cn/chain33?svg=true&branch=master&passingText=Windows%20-%20OK&failingText=Windows%20-%20failed&pendingText=Windows%20-%20pending)](https://ci.appveyor.com/project/33cn/chain33)
[![codecov](https://codecov.io/gh/33cn/chain33/branch/master/graph/badge.svg)](https://codecov.io/gh/33cn/chain33) [![Join the chat at https://gitter.im/33cn/Lobby](https://badges.gitter.im/33cn/Lobby.svg)](https://gitter.im/33cn/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)


# 基于 Chain33 区块链开发框架 开发的DPAC公有链系统

高度模块化, 遵循 KISS原则的区块链开发框架



## Building from source

环境要求: Go 1.19+

## 编译

```shell
git clone https://github.com/DPAC33/DPAC33 $GOPATH/src/github.com/DPAC33/DPAC33
cd $GOPATH/src/github.com/DPAC33/DPAC33
go build -i -o dpac
go build -i -o dpac-cli github.com/DPAC33/DPAC33/cli

```


## 运行

拷贝编译好的dpac, dpac-cli, dpac.toml这三个文件置于同一个文件夹下，执行：

```shell
./dpac -f dpac.toml
```

