## 项目介绍

本次带着大家做的这款动态线程池组件项目，也是各个中大厂中都非常常见的组件能力。通过这样的学习，以中大厂的经验补充自身的技术积累，让自己的简历和职业生涯都有东西可讲。

我们知道，线程池（Thread Pool），是一种基于池化思想管理线程的工具，用于降低资源消耗、提高响应速度、提高线程的管理性。池化技术的引入，可以有效的减少线程频繁申请/销毁和调度所带来的额外开销。对于池化思想，我们还能看到；内存池、连接池、化粪池。

但在实际的工作中，线程池使用的场景非常多，但线程池的参数并不好一次就配置好，同时需要做监控处理，知道整个线程的消耗情况。根据IO密集型，CPU密集型不通过的任务差异，做压测验证调整。所以有一款动态线程池是非常重要的。

### 1. 查看线程池

![img](https://github.com/ruxyeah/dynamic-thread-pool/blob/main/docs/front/img.png?raw=true)

### [#](https://bugstack.cn/md/zsxq/project/dynamic-thread-pool.html#_2-修改线程池)2. 修改线程池

![img](https://github.com/ruxyeah/dynamic-thread-pool/blob/main/docs/front/img_1.png?raw=true)

