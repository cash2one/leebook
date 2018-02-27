# 三层架构与 SSM

---

SSM，即 SpringMVC、Spring 与 MyBatis 三个框架。它们在三层架构中所处的位置是不同的，即它们在三层架构中的功能各不相同，各司其职。

* SpringMVC：作为 View 层的实现者，完成用户的请求接收功能。SpringMVC 的 Controller 作为整个应用的控制器，完成用户请求的转发及对用户的响应。
* MyBatis：作为 Dao 层的实现者，完成对数据库的增、删、改、查功能。
* Spring：以整个应用大管家的身份出现。整个应用中所有 Bean 的生命周期行为，均由 Spring 来管理。即整个应用中所有对象的创建、初始化、销毁，及对象间关联关系的维护，均由 Spring 进行管理。

![](/assets/004.png)