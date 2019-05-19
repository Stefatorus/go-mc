# Go-MC
![](https://img.shields.io/badge/Minecraft-1.14-blue.svg)
![](https://img.shields.io/badge/Protocol-477-blue.svg)
[![Build Status](https://travis-ci.org/Tnze/go-mc.svg?branch=v1.14)](https://travis-ci.org/Tnze/go-mc)

There's some library in Go support you to create your Minecraft client or server.  
这是一些Golang库，用于帮助你编写自己的Minecraft客户端或服务器，
- [x] Mojang authenticate
- [x] Minecraft network protocal
- [x] Parse chat message
- [x] Simple MC robot lib
- [x] Parse NBT

Some examples are at `/cmd` folder.  
有一些例子在cmd目录下

> `1.13.2` version is at [gomcbot](https://github.com/Tnze/gomcbot).

# Getting start
After you install golang tools:
- Run `go run cmd/ping/ping.go` to ping and list the Miaoscraft mc-server.  
- Run `go run cmd/daze/daze.go` to join local server at *localhost:25565* as Steve on offline mode.

See `/bot` folder to get more infomation about how to create your own robot.