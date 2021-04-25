# spring-cloud-gateway-bench

spring cloud gateway是基于webflux的响应式的应用。

本文主要是讲springcloud gateway+nacos，服务注册，来验证下gateway的性能。

项目分两个模块：gateway和consumer

来看下监控下的gateway活跃线程和consumer的活跃线程。通过jemeter测试，100个线程并行执行。
gateway和应用在同一台机器上（8核16G），还有其他的应用在（windows）
大概在6000+到7000的样子。

gateway和应用放到linux环境（2核4G），通过wrk测试下
测试了3次，大概稳定在9000+到10000的样子


关注公众号：木巴沙
![image](https://user-images.githubusercontent.com/26828775/115985915-92422d80-a5e0-11eb-95af-7dffe6bff87d.png)
