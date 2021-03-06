* Jenkins
    * 是一款由Java编写的开源的持续集成工具。

* SonarQube
    * 是一个开源的代码质量管理系统。

* RPC
    * 远程过程调用
    * 在分布式计算，远程过程调用是一个计算机通信协议。该协议允许运行于一台计算机的程序调用另一个地址空间(通常为一个开放网络的一台计算机)的子程序，而程序员就像调用本地程序一样，无需额外地为这个交互作用编程(无需关注细节)。RPC是一种服务器-客户端(Client/Server)模式，经典实现是一个通过发送请求-接受回应进行信息交互的系统。
    * RPC是一种进程间通信的模式，程序分布在不同的地址空间里。如果在同一主机里，RPC可以通过不同的虚拟地址空间（即便使用相同的物理地址）进行通讯，而在不同的主机间，则通过不同的物理地址进行交互。

* Java RMI
    * Java远程方法调用是
    * Java编程语言里，一种用于实现远程过程调用的应用程序编程接口。它使客户机上运行的程序可以调用远程服务器上的对象。远程方法调用特性使Java编程人员能够在网络环境中分布操作。RMI全部的宗旨就是尽可能简化远程接口对象的使用。

* ZooKeeper
    * 它为大型分布式计算提供开源的分布式配置服务、同步服务和命名注册。
    * ZooKeeper的架构通过冗余服务实现高可用性。因此，如果第一次无应答，客户端就可以询问另一台ZooKeeper主机。ZooKeeper节点将它们的数据存储于一个分层的命名空间，非常类似于一个文件系统或一个前缀树结构。客户端可以在节点读写，从而以这种方式拥有一个共享的配置服务。更新是全序的。

* Dubbo
    * 是一款高性能、轻量级的开源Java RPC框架，它提供了三大核心能力: 面向接口的远程方法调用，智能容错和负载均衡，以及服务自动注册和发现。

* ActiveMQ
    * 开放源码消息中间件；由于ActiveMQ是一个纯Java程序，因此只需要操作系统支持Java虚拟机。

* Kafka
    * 该项目的目标是为处理实时数据提供一个统一、高吞吐、低延迟的平台。其持久化层本质上是一个“按照分布式事务日志架构的大规模发布/订阅消息队列”，这使它作为企业级基础设施来处理流式数据非常有价值。此外，Kafka可以通过Kafka Connect连接到外部系统(用于数据输入/输出)，并提供了Kafka Streams(一个Java流式处理库)。

* RabbitMQ
    * 是实现了高级消息队列协议(AMQP)的开源消息代理软件(亦称面向消息的中间件)。

* Redis
    * 是一个使用ANSI C编写的开源、支持网络、基于内存、可选持久性的键值对存储数据库。

* Netty
    * 是一个非阻塞I/O客户端-服务器框架，主要用于开发Java网络应用程序，如协议服务器和客户端。
    * 异步事件驱动的网络应用程序框架和工具用于简化网络编程，例如TCP和UDP套接字服务器。

