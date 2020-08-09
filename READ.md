## springcloud和springboot是什么关系？
springboot为springcloud提供了代码实现环境，使用springboot将其他组件有机融合到了springclud的体系架构中。所以说springclud是基于springboot的微服务系统架构的一站式解决方案。

## springcloud与springboot版本对应关系
springcloud版本     | springboot版本
-------- | -----
Hoxton | 2.2.x, 2.3.x (Starting with SR5)
Greenwich | 2.1.x
Finchley | 2.0.x
Edgware | 1.5.x
Dalston | 1.5.x

[springcloud文档](https://spring.io/projects/spring-cloud#overview)

## springcloud与dubbo技术选型比较
* 架构完整度 dubbo只提供了服务注册和服务治理两个模块 springcloud则是一站式
* 社区活跃度 springcloud的活跃度要比dubbo高
* 通讯协议 dubbo通讯协议采用的是RPC，springcloud采用的是HTTP REST，如果springcloud想使用rpc，可以使用springcloud gRPC模块
* 技术改造还是微服务开发 如果是技术改造，使用dubbo对原有代码改动较少，使用springcloud想到于重新开发，如果是新开始的项目建议使用springcloud