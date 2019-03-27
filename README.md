# dubbo-demo
spring boot 2.1.3 and dubbo 2.7.1 version demo


1. 运行DubboDemoServiceApplication类，启动Dubbo服务端， 
会看见控制台中成功启动：[DUBBO] Register: dubbo://10.168.168.168:20880/com.example.dubbo.demo.api.DemoApi

2. 运行DubboDemoWebApplication类，启动Dubbo客户端

3. 访问：http://localhost:8088/demo/index
   体会Dubbo客户端远程调用Dubbo服务端的全过程！