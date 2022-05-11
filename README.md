# multitail

multitail 可以实现多节点（前提配置好免密）tail文件

最初的需求是Openstack集群多个node节点，nova，neutron，glance，cinder高可用部署在多节点，
查询组件的日志要去每一个节点上去查询，在没有总体日志系统的情况下，想有一个工具，能够同时tail多节点的日志。
不用终端工具开多个窗口去tail日志文件。


v0.1 release
* tail 多节点的文件
* 不同的文件输出用不同的颜色标识
