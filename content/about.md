+++
title = "Zuozhi Wang"
+++

## About Me

{{< figure class="avatar" src="/portrait.jpeg" alt="avatar">}}

I am a sixth year Computer Science PhD student at UC Irvine, under the supervision of Professor [Chen Li](https://chenli.ics.uci.edu). My research focuses are on the areas of distributed big data processing and query optimization. I am on the job market this year :)

## Education
2017-2023 (expected)
:   **PhD, Computer Science**; UC Irvine

2013-2017
:   **BS, Computer Science**; UC Irvine

## Project Highlights

<a href="https://github.com/Texera/texera" style="font-size:1.2em;font-weight:bold;">Texera</a>, a system for scalable and collaborative data analytics using workflows.  
2016 - Present, at UC Irvine  

I am the main contributor of the Texera project (1000+ commits). 
I have worked on virtually all layers of the system, including the distributed dataflow execution engine, RPC services, fault tolerance, compiler, operator library, web services, and the frontend. I have also mentored over 50+ undergraduate and master students on the project.


<a href="https://github.com/alibaba/cost-based-incremental-optimizer" style="font-size:1.2em;font-weight:bold;">Tempura</a>, a cost-based optimizer framework for incremental data processing.   
2018 - 2020, at Alibaba  

I was the main developer of the Tempura optimizer framework, which is built on top of Apache Calcite. I worked on the design of the core query planner and rule engine, introduced 20+ new rewriting rules for incremental processing and incremental view maintenance, and worked on various optimizations. 

Tempura has been deployed into production in [Alibaba MaxCompute](https://www.alibabacloud.com/product/maxcompute) Data Warehouse, and used by more than 10% of queries that run on the platform every day.


## Industrial Experience

**Research Intern at Microsoft Research**, 2020.6 - 2020.9
<!-- Research Intern in the [Data Management, Exploration and Mining (DMX)](https://www.microsoft.com/en-us/research/group/data-management-exploration-and-mining-dmx/) group. -->
- Mentor: [Bailu Ding](https://www.microsoft.com/en-us/research/people/badin/)
- Worked on query optimization in Microsoft SQL Server. Implemented materialized bitmap filters in SQL Server Data Warehouse and designed an algorithm to reuse materialized bitmap filters.

**Research Collaborator at Alibaba**,  2018.6 - 2020.6
<!-- Research Collaborator in the Data Analytics and Intelligence Lab (DAIL). -->
- Mentor: [Kai Zeng](https://kai-zeng.github.io/)
- Worked on [Tempura](https://github.com/alibaba/cost-based-incremental-optimizer), a query optimizer framework for incremental data processing.



## News
<style>
  .news ul {
    padding-left: 0px !important;
  }
  .news ul li {
    margin-bottom: 5px;
  }
</style>

<div class="news" markdown=1>

- 2022-09: Our paper "Fries: Fast and Consistent Runtime Reconfiguration in Dataflow Systems with Transactional Guarantees" accepted by VLDB 2023!
- 2022-09: I participated remotely in our Texera VLDB 2022 demo, with my colleagues in Sydney and me in Irvine working collaboratively on a workflow at the same time.
- 2022-09: I posted my [first blog](https://texera.github.io/blog/data-crawling-using-texera-with-python-user-defined-functions/) on using Texera for web crawling and ETL process.
- 2022-08: I passed my topic defense exam!
- 2022-06: I attended SIGMOD 2022 in person in Philadelphia. It was super fun to attend my first in-person conference after covid!
- 2022-06: Two demo papers accepted by VLDB 2022.

</div>

## Publications
<style>
  .publications ol {
    padding-left: 0px !important;
    border-spacing: 0 5px;
    border-collapse: separate;
  }
</style>

<div class="publications">

1. **Fries: Fast and Consistent Runtime Reconfiguration in Dataflow Systems with Transactional Guarantees**  
**Zuozhi Wang**, Shengquan Ni, Avinash Kumar, Chen Li, to appear in **VLDB 2023**.  
1. **Demonstration of Collaborative and Interactive Workflow-Based Data Analytics in Texera** (demo paper)   
Xiaozhen Liu, **Zuozhi Wang**, Shengquan Ni, Sadeem Alsudais, Yicong Huang, Avinash Kumar, Chen Li, in **VLDB 2022**. [ [PDF] ](https://www.vldb.org/pvldb/vol15/p3738-liu.pdf) [ [Demo Video] ](https://youtu.be/2gfPUZNsoBs)
1. **Optimizing Machine Learning Inference Queries with Correlative Proxy Models**   
Zhihui Yang, **Zuozhi Wang**, Yicong Huang, Yao Lu, Chen Li, X. Sean Wang, in **VLDB 2022**. [ [PDF] ](https://arxiv.org/pdf/2201.00309.pdf) [ [Github] ](https://github.com/ZhihuiYangCS/CorrProxies)
1. **Demonstration of Accelerating Machine Learning Inference Queries with Correlative Proxy Models** (demo paper)   
Zhihui Yang, Yicong Huang, **Zuozhi Wang**, Feng Gao, Yao Lu, Chen Li, X. Sean Wang, in **VLDB 2022**. [ [PDF] ](https://www.vldb.org/pvldb/vol15/p3734-yang.pdf)
1. **Tempura: A General Cost-based Optimizer Framework for Incremental Data Processing**   
**Zuozhi Wang**, Kai Zeng, Botong Huang, Wei Chen, Xiaozong Cui, Bo Wang, Ji Liu, Liya Fan, Dachuan Qu, Zhenyu Hou, Tao Guan, Chen Li, Jingren Zhou, in **VLDB 2021**. [ [PDF] ](http://vldb.org/pvldb/vol14/p14-wang.pdf) [ [Slides] ](https://www.slideshare.net/ZuozhiWang/tempura-a-general-costbased-optimizer-framework-for-incremental-data-processing) [ [Github] ](https://github.com/alibaba/cost-based-incremental-optimizer)
1. **Grosbeak: A Data Warehouse Supporting Resource-Aware Incremental Computing** (demo paper)   
**Zuozhi Wang**, Kai Zeng, Botong Huang, Wei Chen, Xiaozong Cui, Bo Wang, Ji Liu, Liya Fan, Dachuan Qu, Zhenyu Hou, Tao Guan, Chen Li, Jingren Zhou, in **SIGMOD 2020**. [ [PDF] ](https://dl.acm.org/doi/pdf/10.1145/3318464.3384708)
1. **Amber: A Debuggable Dataflow System Based on the Actor Model**   
Avinash Kumar, **Zuozhi Wang**, Shengquan Ni, Chen Li, in **VLDB 2020**. [ [PDF] ](https://vldb.org/pvldb/vol13/p740-kumar.pdf)
1. **Demonstration of Interactive Runtime Debugging of Distributed Dataflows in Texera** (demo paper)   
**Zuozhi Wang**, Avinash Kumar, Shengquan Ni, Chen Li, in **VLDB 2020**. [ [PDF] ](http://www.vldb.org/pvldb/vol13/p2953-wang.pdf) [ [Demo Video] ](https://youtu.be/SP-XiDADbw0)
1. **A Demonstration of TextDB: Declarative and Scalable Text Analytics on Large Data Sets** (**Best Demo Award**)   
**Zuozhi Wang**, Flavio Bayer, Seungjin Lee, Kishore Narendran, Xuxi Pan, Qing Tang, Jimmy Wang, Chen Li, in **ICDE 2017**. [ [PDF]     ](https://chenli.ics.uci.edu/files/icde2017-textdb-demo.pdf) 

</div>

<!-- ## References

* Foo Bar: Head of Department, Placeholder Names, Lorem
* John Doe: Associate Professor, Department of Computer Science, Ipsum

[^1]: This is the first footnote.
[^2]: This is the second footnote. -->