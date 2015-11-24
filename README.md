#基于python的在线聊天服务器程序
这是一个用python写的简单的在线聊天程序。
现在还在开发中，现在只能用命令行交互
##当前版本使用方式
通过telnet连接服务器即可进行通信,可通过telnet连接我的服务器尝试一下
>host:www.cody.wang

>port:5005

##可用指令

| command       | args          | function  |
| ------------- |:-------------:| -----:    |
| login         | login<name>   | login the server with the name       |
| logout        | none          | logout the server     |
| say           | say<message>  | send the message in the room      |
| look          | none          | see the online users in the room      |
| userls        | none          | see the online users on the server      |
| roomls        | none          | see the existing rooms on the server      |
| back          | none          | go back to the main room      |
