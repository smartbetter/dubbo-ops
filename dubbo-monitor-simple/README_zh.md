# dubbo-monitor-simple

dubbo监控中心，用于监控在dubbo框架下接口暴露，注册情况，也可以看接口的调用明细，调用时间等。Simple Monitor 挂掉不会影响到 Consumer 和 Provider 之间的调用，所以用于生产环境不会有风险。Simple Monitor 采用磁盘存储统计信息，请注意安装机器的磁盘限制，如果要集群，建议用mount共享磁盘。

charts 目录必须放在 jetty.directory 下，否则页面上访问不了。
