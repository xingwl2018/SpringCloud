##工程说明

Spring Cloud Eureka，使用Netflix Eureka 来实现服务注册与发现，它既包含了服务端组件（eureka-server），又包含了客户端组件（eureka-client），
并且服务端和客户端均采用Java编写，所以一Eureka主要适用于通过Java实现的分布式系统，或是与JVM兼容语言构建的系统。

Eureka 服务端，又称为服务注册中心，支持高可用。
Eureka 客户端，主要处理服务的注册与发现，客户端服务通过注解和参数配置的方式，嵌入在客户端应用程序中，在应用程序运行时，Eureka 客户端向注册中心注册自身
提供的服务并周期性的发送心跳来更新服务租约。
