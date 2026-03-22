<!-- ==================== HEADER: Typing Animation ==================== -->
<div align="center">
  <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=4000&pause=1000&color=58A6FF&center=true&vCenter=true&multiline=true&repeat=true&width=620&height=100&lines=Hey+%F0%9F%91%8B+I'm+fuyoude;" alt="Typing SVG" /></a>
</div>

<!-- ==================== BADGES: Social & Contact ==================== -->
<div align="center">

  [![GitHub followers](https://img.shields.io/github/followers/fuyoude?style=flat&logo=github&label=Followers)](https://github.com/fuyoude)
  [![Profile Views](https://komarev.com/ghpvc/?username=fuyoude&color=58a6ff&style=flat&label=Profile+Views)](https://github.com/fuyoude)

</div>

---

<!-- ==================== ABOUT ME ==================== -->

## 🧑‍💻 About Me

- 🌱 I'm currently deepening my knowledge in **distributed systems & middleware & OS kernel & network**
- 🛠️ I built a **full-featured RPC framework** from scratch — [netty-rpc](https://github.com/fuyoude/netty-rpc)
- 📖 I've done **line-by-line source code analysis** of Dubbo (13 topics), RocketMQ (8 topics), Spring, and more
- 📓 I maintain a **260+ commit technical notebook** covering everything from x86 assembly to distributed middleware
- 🔬 Past research in **computer vision** — implemented KCF, DSST, MOSSE, Deep SORT, Kalman filters with paper references
- 💬 Ask me about **Dubbo, RocketMQ, Netty, Java concurrency, OS internals, Network**
- ⚡ My future research plan focuses on **xv6, the Linux kernel, and network engineering**
- 🎓 Education: **XJTU, CS / Master's in CV** 
- 🔢 I like digging into how things work — from x86 assembly and OS kernels all the way up to distributed middleware like Dubbo and RocketMQ. I believe understanding the full stack, not just the layer you work on, makes you a better engineer.

---

<!-- ==================== TECH STACK ==================== -->

## 🛠️ Tech Stack

<!-- 🔧 删除你不熟悉的，添加你熟悉的 -->

**Languages**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)    ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![x86 Assembly](https://img.shields.io/badge/x86_Assembly-654FF0?style=flat-square&logo=assemblyscript&logoColor=white)

**Frameworks & Middleware**

![Spring](https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white)  ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)  ![Dubbo](https://img.shields.io/badge/Apache_Dubbo-D22128?style=flat-square&logo=apache&logoColor=white)  ![RocketMQ](https://img.shields.io/badge/RocketMQ-D77310?style=flat-square&logo=apache&logoColor=white)  ![ZooKeeper](https://img.shields.io/badge/ZooKeeper-53A318?style=flat-square&logo=apache&logoColor=white)  ![Apache Mina](https://img.shields.io/badge/Apache_Mina-D22128?style=flat-square&logo=apache&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**Computer Vision** *(past research)*

![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

---

<!-- ==================== FEATURED PROJECTS ==================== -->

## 🔧 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### [netty-rpc](https://github.com/fuyoude/netty-rpc) ⭐
A **lightweight RPC framework** built from scratch with Netty + Zookeeper + Spring (178 commits). Architecturally inspired by Dubbo.

**20+ features including:**
- 🔍 Zookeeper service registration & discovery
- ⚖️ 3 load balancing: Weighted Round Robin, Weighted Random, Consistent Hash
- 🛡️ 4 fault tolerance: Failover, Failback, Failfast, Failsafe
- 🔄 Heartbeat, timeout, reconnection
- 📉 Service degradation & rate limiting
- 🔌 SPI mechanism & filter chain
- 🔐 Token verification & sticky connections
- 📡 TCP / InJVM dual protocol
- ⏱️ Sync & async invocation
- 📊 JMX monitoring & graceful shutdown

</td>
<td width="50%" valign="top">

### [zeromq](https://github.com/fuyoude/zeromq) ⭐
A **lightweight message queue** built on Netty, supporting multi-producer/consumer topologies.

- 🔀 Multi-producer, multi-consumer (M:N)
- 🏘️ Consumer clustering
- 🎯 Keyword-based exact routing
- ⚖️ Consumer load balancing
- 🧵 Async multi-threaded dispatch
- 📦 Ordered delivery & batched dispatch

---

### [java-nio-server](https://github.com/fuyoude/java-nio-server)
Java NIO server implementation for low-level network programming.

### [mina-2.2.0](https://github.com/fuyoude/mina-2.2.0)
Apache Mina 2.2.0 source code research with annotations.

</td>
</tr>
</table>

---

<!-- ==================== TECH BLOG ==================== -->

## 📖 Technical Notebook — [tech-blog](https://github.com/fuyoude/tech-blog)

> 260+ commits of systematic, annotated notes spanning from hardware to distributed systems.

| Layer | Directory | Topics Covered |
|:---:|:---|:---|
| ⚙️ | **[汇编语言 / x86-32](https://github.com/fuyoude/tech-blog/tree/master/汇编语言/x86-32%20汇编)** | x86-32 assembly language, registers, addressing modes, interrupts |
| 🖥️ | **[操作系统](https://github.com/fuyoude/tech-blog/tree/master/操作系统)** | Process management, memory management, file systems, scheduling |
| 🖥️ | **[操作系统之真象还原](https://github.com/fuyoude/tech-blog/tree/master/操作系统之真象还原)** | Building an OS from scratch |
| 🔗 | **[链接\_装载与库](https://github.com/fuyoude/tech-blog/tree/master/链接_装载与库)** | Linkers, loaders, shared libraries |
| ☕ | **[Java 语言](https://github.com/fuyoude/tech-blog/tree/master/Java%20语言)** | Java language deep dives, JVM internals, concurrency |
| 📜 | **[语言规范](https://github.com/fuyoude/tech-blog/tree/master/语言规范)** | Java Language Specification (JLS) & JVM Specification |
| 🌐 | **[计算机网络](https://github.com/fuyoude/tech-blog/tree/master/计算机网络)** | TCP/IP, HTTP, DNS, network protocols |
| 🔌 | **[网络编程](https://github.com/fuyoude/tech-blog/tree/master/网络编程)** | Socket programming, Java NIO, Netty |
| 🔍 | **[源码分析](https://github.com/fuyoude/tech-blog/tree/master/源码分析)** | Source code analysis of frameworks |

---

<!-- ==================== SOURCE CODE ANALYSIS ==================== -->

## 🔍 Source Code Analysis — [Open-Source-Research](https://github.com/fuyoude/Open-Source-Research)

> Line-by-line annotated analysis of major Java frameworks and libraries.

<details>
<summary><b>Apache Dubbo — 13 Topics (click to expand)</b></summary>
<br>

| # | Topic | Description |
|---|---|---|
| 1 | [SPI 机制](https://github.com/fuyoude/Open-Source-Research/blob/master/src/note/dubbo/dubbo%20source/DubboSPI.java) | Dubbo's Service Provider Interface and extension loading |
| 2 | [自适应扩展](https://github.com/fuyoude/Open-Source-Research/blob/master/src/note/dubbo/dubbo%20source/DubboAdaptive.java) | Adaptive extension mechanism |
| 3 | [服务导出](https://github.com/fuyoude/Open-Source-Research/blob/master/src/note/dubbo/dubbo%20source/DubboExporter.java) | Service export flow |
| 4 | [服务引用](https://github.com/fuyoude/Open-Source-Research/blob/master/src/note/dubbo/dubbo%20source/DubboReference.java) | Service reference flow |
| 5 | [服务调用](https://github.com/fuyoude/Open-Source-Research/blob/master/src/note/dubbo/dubbo%20source/DubboServiceInvokingProcess.java) | Service invocation process |
| 6 | [集群容错](https://github.com/fuyoude/Open-Source-Research/blob/master/src/note/dubbo/dubbo%20source/DubboCluster.java) | Cluster fault tolerance |
| 7 | [服务目录](https://github.com/fuyoude/Open-Source-Research/blob/master/src/note/dubbo/dubbo%20source/DubboDirectory.java) | Service directory |
| 8 | [负载均衡](https://github.com/fuyoude/Open-Source-Research/blob/master/src/note/dubbo/dubbo%20source/DubboLoadBalance.java) | Load balancing strategies |
| 9 | [过滤器](https://github.com/fuyoude/Open-Source-Research/blob/master/src/note/dubbo/dubbo%20source/DubboFilter.java) | Filter chain |
| 10 | [服务降级](https://github.com/fuyoude/Open-Source-Research/blob/master/src/note/dubbo/dubbo%20source/DubboMock.java) | Service degradation (Mock) |
| 11 | [本地服务](https://github.com/fuyoude/Open-Source-Research/blob/master/src/note/dubbo/dubbo%20source/DubboInjvm.java) | InJVM local service |
| 12 | [Wrapper](https://github.com/fuyoude/Open-Source-Research/blob/master/src/note/dubbo/dubbo%20source/DubboWrapper.java) | Wrapper mechanism |
| 13 | [Zookeeper](https://github.com/fuyoude/Open-Source-Research/blob/master/src/note/dubbo/dubbo%20source/DubboZookeeperAnalysis.java) | Zookeeper connection analysis |

</details>

<details>
<summary><b>Apache RocketMQ — 8 Topics (click to expand)</b></summary>
<br>

| # | Topic | Description |
|---|---|---|
| 1 | [概述](https://github.com/fuyoude/zeromq/issues/1) | RocketMQ overview & architecture |
| 2 | [NameServer](https://github.com/fuyoude/Open-Source-Research/blob/master/src/note/rocketmq/rocketmq-source/RocketmqNameServerAnalysis.java) | Route registration & discovery |
| 3 | [Producer](https://github.com/fuyoude/Open-Source-Research/blob/master/src/note/rocketmq/rocketmq-source/RocketmqProducerAnalysis.java) | Message producer analysis |
| 4 | [消息消费](https://github.com/fuyoude/Open-Source-Research/blob/master/src/note/rocketmq/rocketmq-source/RocketmqPushConsumerAnalysisOne.java) | Push consumer internals |
| 5 | [消息存储](https://github.com/fuyoude/Open-Source-Research/blob/master/src/note/rocketmq/rocketmq-source/RocketmqMessageStoreAnalysisOne.java) | CommitLog, ConsumeQueue, IndexFile |
| 6 | [高可用](https://github.com/fuyoude/Open-Source-Research/blob/master/src/note/rocketmq/rocketmq-source/RocketmqHAAnalysis.java) | Master-Slave replication & HA |
| 7 | [远程通信](https://github.com/fuyoude/Open-Source-Research/blob/master/src/note/rocketmq/rocketmq-source/RocketmqRemotingAnalysis.java) | Netty-based remoting layer |
| 8 | [事务消息](https://github.com/fuyoude/Open-Source-Research/blob/master/src/note/rocketmq/rocketmq-source/RocketmqTransactionAnalysis.java) | Transaction message implementation |

</details>

<details>
<summary><b>Spring, Concurrency, Collections & More (click to expand)</b></summary>
<br>

**Spring Framework**
| Topic | Link |
|---|---|
| IoC 启动流程 | [SpringIOCBootAnalysis.java](https://github.com/fuyoude/Open-Source-Research/blob/master/src/note/spring/SpringIOCBootAnalysis.java) |
| AOP 源码分析 | [SpringAopAnalysis.java](https://github.com/fuyoude/Open-Source-Research/blob/master/src/note/spring/SpringAopAnalysis.java) |

**Concurrency**
| Topic | Link |
|---|---|
| ThreadPoolExecutor | [ThreadPoolExecutorAnalysis.java](https://github.com/fuyoude/Open-Source-Research/blob/master/src/note/concurrent/ThreadPoolExecutorAnalysis.java) |
| ThreadLocal | [ThreadLocalAnalysis.java](https://github.com/fuyoude/Open-Source-Research/blob/master/src/note/concurrent/ThreadLocalAnalysis.java) |
| ListenableFuture | [ListenableFutureAnalysis.java](https://github.com/fuyoude/Open-Source-Research/blob/master/src/note/concurrent/ListenableFutureAnalysis.java) |
| ExecutorCompletionService | [ExecutorCompletionServiceAnalysis.java](https://github.com/fuyoude/Open-Source-Research/blob/master/src/note/concurrent/ExecutorCompletionServiceAnalysis.java) |

**Collections**
| Topic | Link |
|---|---|
| HashMap (JDK 1.6) | [HashMapAnalysis.java](https://github.com/fuyoude/Open-Source-Research/blob/master/src/note/collection/HashMapAnalysis.java) |
| HashMap (JDK 1.8) | [HashMap8Analysis.java](https://github.com/fuyoude/Open-Source-Research/blob/master/src/note/collection/HashMap8Analysis.java) |
| List | [ListAnalysis.java](https://github.com/fuyoude/Open-Source-Research/blob/master/src/note/collection/ListAnalysis.java) |

**SSL / Security**
| Topic | Link |
|---|---|
| JCA 体系结构 | [ssl/jca/](https://github.com/fuyoude/Open-Source-Research/tree/master/src/note/ssl/jca) |
| KeyStore | [KeyStoreAnalysis.java](https://github.com/fuyoude/Open-Source-Research/blob/master/src/note/ssl/keystore/KeyStoreAnalysis.java) |

</details>

---

<!-- ==================== CV RESEARCH ==================== -->

## 🔬 Computer Vision Research — [learning](https://github.com/fuyoude/learning)

> 13 ⭐ · Implementations of classical CV algorithms with academic paper references and detailed annotations.

| Category | Algorithm | Paper Reference |
|---|---|---|
| **Tracking** | [KCF](https://github.com/fuyoude/learning/tree/master/correlation_filter) | Kernelized Correlation Filters |
| | [DSST](https://github.com/fuyoude/learning/tree/master/correlation_filter) | Discriminative Scale Space Tracker |
| | [MOSSE](https://github.com/fuyoude/learning/tree/master/correlation_filter) | Minimum Output Sum of Squared Error |
| | [Mean Shift](https://github.com/fuyoude/learning/blob/master/mean_shift_tracking/mean_shift_tracker.py) | Mean Shift Tracking |
| | [Deep SORT](https://github.com/fuyoude/learning/blob/master/deep_sort/deep_sort_app.py) | Multi-Object Tracking |
| | [MKCF](https://github.com/fuyoude/learning/tree/master/mkcf) | arXiv:1611.02364 |
| **Filtering** | [Kalman Filter](https://github.com/fuyoude/learning/blob/master/kalman_filter/kf/kalman_filter.py) | Standard & Extended KF |
| | [Guided Filter](https://github.com/fuyoude/learning/blob/master/guided_filter/main.py) | Edge-preserving smoothing |
| | [Dark Channel](https://github.com/fuyoude/learning/blob/master/dark_channel/dehaze.py) | Image dehazing |
| **Features** | [Harris Corner](https://github.com/fuyoude/learning/blob/master/corner_detection/harris_corner_detection.py) | Corner detection |
| | [LBP](https://github.com/fuyoude/learning/blob/master/local_binary_pattern/local_binary_pattern.py) | Local Binary Pattern |
| **Modeling** | [GMM + EM](https://github.com/fuyoude/learning/blob/master/gaussian/gaussian_mixture_model.py) | Gaussian Mixture Model |
| | [Background Model](https://github.com/fuyoude/learning/blob/master/gauss_mix/gauss_mix.py) | ICCV'04 Improved Adaptive GMM |
| **Blur Detection** | [Blur Features](https://github.com/fuyoude/learning/tree/master/blur) | CVPR'08, CVPR'14 papers |

---

<!-- ==================== GITHUB STATS ==================== -->

## 📊 GitHub Stats

<div align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=fuyoude&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" alt="GitHub Stats" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=fuyoude&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top Languages" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=fuyoude&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</div>

---

<!-- ==================== PHILOSOPHY ==================== -->

<div align="center">
  <i>"The best way to understand a system is to build one."</i>
  <br><br>
  I learn by reading source code and rebuilding things from scratch.<br>
  Most of my repos are heavily annotated — they're meant to be <b>read</b>, not just run.
</div>

---

<!-- ==================== FOOTER ==================== -->

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>
</div>

