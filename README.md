Anywhere 随启随用的静态文件服务器
=====================

Running static file server anywhere. 随时随地将你的当前目录变成一个静态文件服务器的根目录。

Anywhere(v2)
============

- add error handle on startup 添加启动时的异常处理,例如端口占用

## Installation
```
npm install anywhere2 -g
```

## Execution
```
$ anywhere
// or with port
$ anywhere -p 8000
// or start it but silent(don't open browser)
$ anywhere -s
// or with hostname
$ anywhere -h localhost -p 8888
// or with folder
$ anywhere -d ~/git/anywhere
```

## Help
```
$ anywhere --help
Usage:
  anywhere --help // print help information
  anywhere // 8000 as default port, current folder as root
  anywhere 8888 // 8888 as port
  anywhere -p 8989 // 8989 as port
  anywhere -s // don't open browser
  anywhere -h localhost // localhost as hostname
  anywhere -d /home // /home as root
```

## Visit

```
http://localhost:8000
```
执行命令后，默认浏览器将为您自动打开主页。

## License
The MIT license.
