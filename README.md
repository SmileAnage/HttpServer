HTTPServer
===

### httpserver部分

>获取http请求

>解析http请求

>将请求发送给WebFrame

>从WebFrame接受反馈数据

>将数据组织委员Response格式发送给客户端

### WebFrame部分

>从httpserver接收具体请求

>根据请求进行逻辑处理和数据处理

>将需要的数据反馈给httpserver

### 技术点

>httpserver部分需要与两端建立通信

>webFrame部分采用多路复用接收并发请求

>数据传递使用json格式
