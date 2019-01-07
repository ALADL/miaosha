### 生产内存环境

    有问题或者宝贵意见联系我的QQ,非常希望你的加入！
## 前言

    注重实践,不会长篇大论,纯属浪费大家时间！属于进阶文章,感谢你的支持！
    
    
    解决问题：
    |_ 1.生产环境发生了内存溢出该如何处理 
    |_ 2.生产环境应该给服务器分配多少的内存
    |_ 3.如何对垃圾回收起的性能进行调优
    |_ 4.生产环境CPU的负载飙高应该如何处理
    |_ 5.生产环境因该给应用分配多少的线程合适
    |_ 6.不加log如何确定请求是否执行到某一段的代码 
    |_ 7.实时查看某个方法的入参与返回值 
    |_ 8.JVM的字节码实操
    |_ 9.循环体中字符串拼接为什么效率很低 
    |_ 10.string常量池怎么回事
    |_ 11.用字节码分析 i++，++i 到底哪种效率高 
    
    
    项目实战收获：
    
     |_ 1.熟练使用各种监控和调试工具 
     |_ 2.从容应对生产环境的各种调试和性能
     |_ 3.熟悉JVM字节码指令
     |_ 4.深入理解JVM自动回收机制学会GC调优
     |_ 5.基于JDK命令行的监控 |_ JVM的参数类型 
                           |_ 查看JVM运行时的参数
                           |_ Jstat查看JVM统计信息 
                           |_ 演示内存溢出
                           |_ 导出内存映像文件
                           |_ MAT分析内存溢出
                           |_ jstack与线程的状态
                           |_ jstack实战死循环与锁
     |_ 6.基于JVisualVM的可视化工具 |_ 监控本地java进程
                                 |_ 监控远程java进程
     |_ 7.基于Btrace的监控调试基于Btrace的监控调试 |_ Btrace入门
                                              |_ 拦截器构造函数，同名函数
                                              |_ 拦截器返回值，异常，行号
                                              |_ 拦截器复杂参数，环境变量，正则匹配拦截
                                              |_ 注意事项                
     |_ 8.tomcat的性能监控调优 |_ tomcat远程debug
                            |_ tomcat-manager监控
                            |_ psi-probe监控 
                            |_ tomcat优化
     |_ 9.nginx的监控调优 |_ nginx的监控调优
                        |_ ngx_http_stub_status监控连接信息
                        |_ ngxtop监控请求信息
                        |_ nginx-rrd图形化监控
                        |_ nginx优化
     |_ 10.jvm+gc调优 |_ JVM的内存结构以及各个分区
                     |_ 常见垃圾回收算法
                     |_ 垃圾回收期调优
                     |_ 如何分析内存日志
                     |_ 垃圾回收器 
                     |_ GC日志格式详解
                     |_ ParallelGC调优
                     |_ G1调优