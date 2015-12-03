#接口定义文档
###客户端
|function|send format          |return         |remark        |
|--------|---------------------|---------------|--------------|
|login   |login&name           |1:success;0:failed|处理登录|
|getmember|getmember|[list]|获取服务器在线成员名字列表|
|talkto|talkto&name&message|1:success;0:target user offline;-1:other error|一对一聊天|
|handletalk|


###回调函数id------>sFuncId
正整数：执行正常的回调函数

0：出错

-1：后面的内容为为服务器中一位用户发送过来的信息
