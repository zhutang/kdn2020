# kdn2020
知识定义网络项目-2020大创

## 技术栈（更新中）
- GitHub Desktop使用指南
  - https://www.jianshu.com/p/a6fc842f501d

- 操作系统: Ubuntu 14.04, 16.04.

- SDN网络仿真环境（mininet）
  - mininet 2.2.2（https://github.com/mininet/mininet ）
  - mininet虚拟机（https://github.com/mininet/mininet/releases ）
    - mininet版本2.2.2，操作系统ubuntu14.04 amd64, OVS版本2.0.2, 默认使用openflow1.0
    - mininet/example/tree1024.py: 1024 host, 33 OVS switch，1 controller
    - mininet入门教程（含拓扑构建） - https://github.com/mininet/mininet/wiki/Introduction-to-Mininet
  - OpenvSwitch（https://github.com/openvswitch/ovs ）
    - mininet学习之OVS指令 （https://blog.csdn.net/qq_37831759/article/details/110821597 ）
    - 官方文档（https://docs.openvswitch.org/en/latest/tutorials/ ）
    - 简单拓扑流表配置 - 
  - SDN控制器Ryu（https://github.com/faucetsdn/ryu ）
    - RYU入门教程（含L2Swtich源码） - https://www.sdnlab.com/1785.html
  - 数据中心网络架构的问题与演进 — CLOS网络与Fat-Tree、Spine-Leaf架构（https://www.cnblogs.com/jmilkfan-fanguiju/p/11825042.html ）

- 网络流量监控（sFlow）
  - 基于Mininet的网络流量监控（https://www.sdnlab.com/3760.html ）
  - mininet初步使用，sFlow流量监测（https://blog.csdn.net/qq_30135289/article/details/79547382 ）
    - sFlow Collector（http://www.inmon.com/products/sFlow-RT/sflow-rt.tar.gz ）
    - https://sflow-rt.com/download.php
      - wget https://inmon.com/products/sFlow-RT/sflow-rt.tar.gz
      - tar -xvzf sflow-rt.tar.gz
      - ./sflow-rt/start.sh
      - sudo apt-get install openjdk-7-jdk --- 然而需要sFlow-RT requires Java 1.8+，考虑在Ubuntu 14.04中安装jdk1.8，已安装完成
        - https://www.cnblogs.com/duoban/p/11342929.html
  - sFlow流量可视化应用（https://github.com/sflow-rt/flow-graph ）
  - API（https://sflow-rt.com/reference.php ）

- 强化学习算法（tensorflow）
  - https://github.com/tensorflow/tensorflow
  - https://blog.csdn.net/u011517132/article/details/105118510
  - https://github.com/MorvanZhou/Reinforcement-learning-with-tensorflow/blob/master/contents/10_A3C/A3C_continuous_action.py

- 知识图谱
  - 图数据库（https://github.com/JanusGraph/janusgraph ）
  - 图数据库（https://github.com/neo4j/neo4j ）
  - 规则引擎（https://github.com/kiegroup/drools ）

## 项目时间进度安排
- 基本环境搭建 - 3月
- 技术原理熟悉 - 3月
- 新型算法设计 - 3月
- 新型算法实现 - 3月
- 新型算法测试 - 3月
