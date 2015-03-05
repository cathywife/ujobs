# Ujobs是什么 

基于saltstack进行二次开发，旨在为运维提供一个可以批量控制和操作分布在各地的大规模机器。以作业为核心，底层封装各类OS层原子操作，前端运维可根据需求场景自由编排任务，运维人员在web界面可集中地、并发地、不需要登录主机完成任何运维操作。

# Ujobs解决哪些问题

* 如何远程管理控制业务机器?   
* 如何集中化操作大量机器?   
* 如何从大规模分布的机器上拉取文件?   
* 如何在分布各IDC的机器上批量执行脚本?   
* 如何向大规模分布的机器上分发文件?   
* 如何根据运维需求任意编排任务并执行?   
* 如何跨平台，如何固化并复用运维任务?

# 逻辑架构
参考saltstack/halite项目
* https://github.com/saltstack/halite

# 部署方案

![image](https://github.com/crueluncle/ujobs/raw/master/res/a.jpg)
