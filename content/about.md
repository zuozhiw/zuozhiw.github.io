+++
title = "Zuozhi Wang"
+++

## About Me

{{< figure class="avatar" src="/portrait.jpeg" alt="avatar">}}
I'm a software engineer at [Observe Inc](https://www.observeinc.com/), working on query optimizations of large declarative pipelines.   
I graduated with my PhD in Computer Science from UC Irvine in 2023, under the supervision of Professor [Chen Li](https://chenli.ics.uci.edu). My research focuses are on the areas of distributed data processing and query optimization.

Email:  zuozhi.wang  [at]  observeinc  [dot]  com

## Education
2017-2023
:   **PhD, Computer Science**; UC Irvine

2013-2017
:   **BS, Computer Science**; UC Irvine


## Experiences

**Software Engineer at Observe**, 2023.7 - Present

I'm working on query optimizations on a large-scale observability data lake.

I worked on various components of the in-house query compiler/optimizer. Implemented full-text inverted index support in query optimizer from the ground up and worked on evaluations and optimizations of complex boolean full-text queries.

**PhD Student at UC Irvine**, 2017.9 - 2023.6

I was a main contributor of the Texera project (1000+ commits). Texera is a distributed workflow-based data processing system. It supports Google-Doc like real-time collaborations, responsive runtime interactions, and rich debugging capabilities.

I have worked on virtually all layers of the system, including the distributed dataflow execution engine, RPC services, fault tolerance, compiler, operator library, web services, and the frontend. I have also mentored over 50+ undergraduate and master students on the project.


**Research Intern at Microsoft Research**, 2020.6 - 2020.9
<!-- Research Intern in the [Data Management, Exploration and Mining (DMX)](https://www.microsoft.com/en-us/research/group/data-management-exploration-and-mining-dmx/) group. -->
Worked on query optimization in Microsoft SQL Server. Implemented materialized bitmap filters in SQL Server Data Warehouse and designed an algorithm to reuse materialized bitmap filters.

Mentor: [Bailu Ding](https://www.microsoft.com/en-us/research/people/badin/)

**Research Collaborator with Alibaba**,  2018.6 - 2020.6
<!-- Research Collaborator in the Data Analytics and Intelligence Lab (DAIL). -->
I was a main developer of the [Tempura](https://github.com/alibaba/cost-based-incremental-optimizer) optimizer framework, which is built on top of Apache Calcite. I worked on the design of the core query planner and rule engine, introduced 20+ new rewriting rules for incremental processing and incremental view maintenance, and worked on various optimizations. 

Tempura has been deployed into production in [Alibaba MaxCompute](https://www.alibabacloud.com/product/maxcompute) Data Warehouse, and used by more than 10% of queries that run on the platform every day.

Mentor: [Kai Zeng](https://kai-zeng.github.io/)


## Publications
<style>
  .publications ol {
    padding-left: 0px !important;
    border-spacing: 0 5px;
    border-collapse: separate;
  }
</style>

<div class="publications">

1. Texera: A System for Collaborative and Interactive Data Analytics Using Workflows,    
**Zuozhi Wang**, Yicong Huang, Shengquan Ni, Avinash Kumar, Sadeem Alsudais, Xiaozhen Liu, Xinyuan Lin, Yunyan Ding, Chen Li, to appear in **VLDB 2024**.
1. Demonstration of Udon: Line-by-line Debugging of User-Defined Functions in Data Workflows,   
Yicong Huang, **Zuozhi Wang**, and Chen Li, in **SIGMOD 2024** (**Best Demo Honorable Mention**). [ [PDF] ](https://dl.acm.org/doi/pdf/10.1145/3626246.3654756) [ [Video] ](https://youtu.be/UGOa1XJMeA8?si=K1k0BiE7c2vtQ2Fu)
1. Udon: Efficient Debugging of User-Defined Functions in Big Data Systems with Line-by-Line Control,   
Yicong Huang, **Zuozhi Wang**, and Chen Li, in **SIGMOD 2024**. [ [PDF] ](https://dl.acm.org/doi/pdf/10.1145/3626712)
1. How the experience of California wildfires shape Twitter climate change framings,   
Jessie W. Y. Ko, Shengquan Ni, Alexander Taylor, Xiusi Chen, Yicong Huang, Avinash Kumar, Sadeem Alsudais, **Zuozhi Wang**, Xiaozhen Liu, Wei Wang, Chen Li, and Suellen Hopfer, in **Climate Change 2024**.  [ [PDF] ](https://link.springer.com/article/10.1007/s10584-023-03668-0)
1. Building a Collaborative Data Analytics System: Opportunities and Challenges,   
**Zuozhi Wang**, Chen Li, in **VLDB 2023** (Tutorial). [ [PDF] ](https://www.vldb.org/pvldb/vol16/p3898-wang.pdf)
1. Using Texera to Characterize Climate Change Discussions on Twitter During Wildfires,   
Shengquan Ni, Yicong Huang, Jessie W. Y. Ko, Alexander Taylor, Xiusi Chen, Avinash Kumar, Sadeem Alsudais, **Zuozhi Wang**, Xiaozhen Liu, Wei Wang, Suellen Hopfer, and Chen Li, in Data Science Day at **KDD 2023** (Poster).
1. Tempura: a general cost-based optimizer framework for incremental data processing (Journal Version),   
**Zuozhi Wang**, Kai Zeng, Botong Huang, Wei Chen, Xiaozong Cui, Bo Wang, Ji Liu, Liya Fan, Dachuan Qu, Zhenyu Hou, Tao Guan, Chen Li, Jingren Zhou, in **VLDB Journal 2023**. [ [PDF] ](/tempura-journal.pdf)
1. Fries: Fast and Consistent Runtime Reconfiguration in Dataflow Systems with Transactional Guarantees,   
**Zuozhi Wang**, Shengquan Ni, Avinash Kumar, Chen Li, in **VLDB 2023**.   [ [PDF] ](https://www.vldb.org/pvldb/vol16/p256-wang.pdf) [ [Extended Version] ](https://arxiv.org/pdf/2210.10306.pdf)
1. Demonstration of Collaborative and Interactive Workflow-Based Data Analytics in Texera,   
Xiaozhen Liu, **Zuozhi Wang**, Shengquan Ni, Sadeem Alsudais, Yicong Huang, Avinash Kumar, Chen Li, in **VLDB 2022**  (Demo). [ [PDF] ](https://www.vldb.org/pvldb/vol15/p3738-liu.pdf) [ [Demo Video] ](https://youtu.be/2gfPUZNsoBs)
1. Optimizing Machine Learning Inference Queries with Correlative Proxy Models,   
Zhihui Yang, **Zuozhi Wang**, Yicong Huang, Yao Lu, Chen Li, X. Sean Wang, in **VLDB 2022**. [ [PDF] ](https://arxiv.org/pdf/2201.00309.pdf) [ [Github] ](https://github.com/ZhihuiYangCS/CorrProxies)
1. Demonstration of Accelerating Machine Learning Inference Queries with Correlative Proxy Models,   
Zhihui Yang, Yicong Huang, **Zuozhi Wang**, Feng Gao, Yao Lu, Chen Li, X. Sean Wang, in **VLDB 2022**  (Demo). [ [PDF] ](https://www.vldb.org/pvldb/vol15/p3734-yang.pdf)
1. Tempura: A General Cost-based Optimizer Framework for Incremental Data Processing,   
**Zuozhi Wang**, Kai Zeng, Botong Huang, Wei Chen, Xiaozong Cui, Bo Wang, Ji Liu, Liya Fan, Dachuan Qu, Zhenyu Hou, Tao Guan, Chen Li, Jingren Zhou, in **VLDB 2021**. [ [PDF] ](http://vldb.org/pvldb/vol14/p14-wang.pdf) [ [Slides] ](https://www.slideshare.net/ZuozhiWang/tempura-a-general-costbased-optimizer-framework-for-incremental-data-processing) [ [Video] ](https://www.youtube.com/watch?v=VxPSsRD5afU) [ [Github] ](https://github.com/alibaba/cost-based-incremental-optimizer)
1. Grosbeak: A Data Warehouse Supporting Resource-Aware Incremental Computing,   
**Zuozhi Wang**, Kai Zeng, Botong Huang, Wei Chen, Xiaozong Cui, Bo Wang, Ji Liu, Liya Fan, Dachuan Qu, Zhenyu Hou, Tao Guan, Chen Li, Jingren Zhou, in **SIGMOD 2020** (Demo). [ [PDF] ](https://dl.acm.org/doi/pdf/10.1145/3318464.3384708)
1. Amber: A Debuggable Dataflow System Based on the Actor Model,   
Avinash Kumar, **Zuozhi Wang**, Shengquan Ni, Chen Li, in **VLDB 2020**. [ [PDF] ](https://vldb.org/pvldb/vol13/p740-kumar.pdf)
1. Demonstration of Interactive Runtime Debugging of Distributed Dataflows in Texera,   
**Zuozhi Wang**, Avinash Kumar, Shengquan Ni, Chen Li, in **VLDB 2020** (Demo). [ [PDF] ](http://www.vldb.org/pvldb/vol13/p2953-wang.pdf) [ [Demo Video] ](https://youtu.be/SP-XiDADbw0)
1. A Demonstration of TextDB: Declarative and Scalable Text Analytics on Large Data Sets, (**Best Demo Award**)   
**Zuozhi Wang**, Flavio Bayer, Seungjin Lee, Kishore Narendran, Xuxi Pan, Qing Tang, Jimmy Wang, Chen Li, in **ICDE 2017** (Demo). [ [PDF]     ](https://chenli.ics.uci.edu/files/icde2017-textdb-demo.pdf) 

</div>

<!-- ## References

* Foo Bar: Head of Department, Placeholder Names, Lorem
* John Doe: Associate Professor, Department of Computer Science, Ipsum

[^1]: This is the first footnote.
[^2]: This is the second footnote. -->
