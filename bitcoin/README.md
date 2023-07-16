1 tomcat服务启动
    已完成IDEA启动，未完成tomcat直接启动
    IDEA配置：D:\WorkHome\opensource\bitcoin\WebContent
    TODO 1 打包发tomcat 2 Spring集成

2 websocket启动：启动tomcat即可
    访问路径是 ws://ip:port/context-path/endpoint

3 定义和实现Endpoint
    编程式 注解式

4 Endpoint依赖传递 1 maven引用 2 WEB-INF/lib包
    例如 由于引入<artifactId>chatgpt</artifactId>包 间接启动了@ServerEndpoint("/websocket/chat")
    'ws://localhost:8080/bitcoin/websocket/chat'