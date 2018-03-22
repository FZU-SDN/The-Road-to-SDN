# The Road to SDN

This page gives the steps of learning Software Defined Networking.

Hint: The following repository collects a series of relevant resources of SDN. We recommend you to read it first: [awesome-sdn](https://github.com/sdnds-tw/awesome-sdn)

## Download

This repository has submodules so that you should clone it as follows:

```
git submodule update --init --recursive
```

To update submodules:

```
git submodule update --remote --merge
```

## The Road to SDN

| Step                         | Prerequisite knowledge   | Time   | Difficulty   |
| ---------------------------- | ---- | ---- | ---- |
| 0.Coursera: Network History  | No   | 1 month  | middle    |
| 1.TCP/IP protocol stack      | No   | 2 month  | middle    |
| 2.SDN Course 2013/2014       | 1    | 1 month  | middle    |
| 3.《重构网络：SDN架构与实现》  |  No  | 1 month  | middle    |
| 4.开设博客，Github            | No   | 1 week   | easy      |
| 5.Linux操作系统，Ubuntu       |  No  | a period of time | middle    |
| 6.mininet: Learning by Doing | 5    | a period of time | easy      |

## Learning Resources

**0.Coursera Network History:**

This link is useful for those who do not have any basic knowledge of computer networks.

- [Coursera - University of Michigan, Internet History](https://www.coursera.org/learn/internet-history)

**1. TCP/IP**

- [Coursera - TCP/IP and Advanced Topics](https://www.coursera.org/learn/tcp-ip-advanced)
- [TCP/IP详解 卷1：协议](https://book.douban.com/subject/4707725/)
- [计算机网络（第5版）](https://book.douban.com/subject/10510747/)


**2.SDN Course:**

- [Nick Feamster SDN course1](https://www.youtube.com/watch?v=I-XdDffLMqc&list=PLpherdrLyny-4Y6jXKvi0Ia9jJAk3M_Bs)
- [Nick Feamster SDN course2](https://www.youtube.com/watch?v=dkUDUb9GtH0&list=PLpherdrLyny8YN4M24iRJBMCXkLcGbmhY)


**3.《重构网络》：**

- [SDNLAB_《重构网络》](http://www.sdnlab.com/book/18762.html)

**4.Linux/mininet：**

- [Linux命令行与shell脚本编程大全](https://book.douban.com/subject/26854226/)

Installation：

- [通过脚本快速安装Open vSwitch2.3.0和Mininet](http://www.sdnlab.com/3046.html)

Learning guide：

- [mininet学习指南 李呈](http://www.sdnlab.com/11495.html)

Controller：

(1)OpenDayLight:

- [OpenDaylight与Mininet应用实战之基本环境搭建](http://www.sdnlab.com/1749.html)

(2)Ryu:

- [RYU Github](https://github.com/osrg/ryu)
- [RYU 入门教程](http://www.sdnlab.com/1785.html)
- [RYU tutorial](http://ryu.readthedocs.io/en/latest/getting_started.html)
- [《RYU BOOK》](https://github.com/peiqiaoWang/The-Road-to-SDN/blob/master/RYU/Ryubook.pdf)

Data plane devices：

(1)Open vSwitch:

- [OVS基本命令](https://github.com/peiqiaoWang/The-Road-to-SDN/blob/master/OVS/ovs-commands-reference.pdf)

(2)P4:

- [P4 Tutorials](https://github.com/p4lang/tutorials)
- [P4 Environment Installer](https://github.com/Wasdns/p4Installer)
- [The Road to P4](https://github.com/Wasdns/The-Road-to-P4)
- [P4 Consortium Website](http://p4.org/)
- [Open SDN Engineer Skill Map: P4](https://github.com/PONOUBA/opensdn_engineer_skill_map/blob/master/skill_map_md/data_plane.md#p4)
- [Github: p4lang](https://github.com/p4lang)

**5.Introduction papers：**

- 《The road to SDN - an intellectual history of programmable networks》
- 《OpenFlow: Enabling Innovation in Campus Networks》
- 《Software-Defined Networking: A Comprehensive Survey》

Hint：They can be acquired from:

- School library homepage => Journal => IEEE or ACM Search
- Google academic search

**6.Experiment platform：**

- [SDNLAB 实验平台](http://www.sdnlab.com/1749.html)
- [SDNLAB SDN Guide](http://www.sdnlab.com/sdn-guide/)
