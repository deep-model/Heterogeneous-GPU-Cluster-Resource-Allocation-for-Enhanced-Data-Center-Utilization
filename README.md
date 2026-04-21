[Veiw Project White Paper PDF](https://github.com/deep-model/GPU_Utilization_of_Heterogenous_Clusters/blob/main/GPU%20Utilization_M.Harper.pdf)
# Heterogeneous GPU Cluster Resource Allocation for Enhanced Data Center Utilization
##  Matthew Harper 
## [Veiw Project List](https://github.com/deep-model?tab=repositories)

 <img width="400" height="300" alt="image" src="https://github.com/deep-model/Data_Center_Utilization_of_Heterogenous_GPU_Clusters/blob/main/Multi-tenant%20DC%20Availability.jpg" /> 
  
 
  
  
# Abstract
As data center big data processing systems and deep learning models have become increasingly significant and applied to many 
real-world applications, graphical processing unit (GPU) clusters with in-memory processing have become the 
primary processor choice for powerful high performance computing systems featuring in-memory capabilities for 
deep networks [1,13]. While these in-memory processing capabilities of GPUs exhibit powerful processing 
advantages when applied to deep model processing including speeds of up to 100x faster than batch 
approaches, they present challenges in resource management as a result of their lack of intra-processor 
sharing ability and associated specifications for resource management and schedulers. These challenges leave 
many cloud computing providers with distributed GPU cluster architectures which exhibit high rates of under- 
utilization and discretized periods of start and stop processing [1,3,12,13]. Common approaches to enhance 
GPU utilization and processing performance such as fairness and over-subscribing among others to counter 
GPU cluster hardware resource interference and the contribution to reduced performance and resulting under- 
utilization. creation is not slowing but increasing exponentially. Moreover, the increase in data creation and 
big data processing systems requirements of high performance in memory computing, has led to the development and use 
of advanced distributed computing techniques such as distributed-parallel computing, cloud computing, clustering, 
and high-performance computing integrated with heterogeneous computing infrastructures consisting of layered 
virtualization over multiple variations of concurrent CPU and GPU environments [33]. 

 <img width="600" height="400" alt="image" src="https://github.com/deep-model/Data_Center_Utilization_of_Heterogenous_GPU_Clusters/blob/main/NVLink%20Cluster.jpg" />

However, these resource allocation optimization approaches each present less than ideal optimized solutions for 
generalized heterogenous GPU clusters [1, 12]. Moreover, for specific applications one or more of these pragmatic 
approaches may work well for the intended application. However, in today’s modern generalized data centers and 
cloud computing distributed clusters, a more generalized approach is often the more highly desired outcome for 
holistic performance perspectives [1]. This work presents an overview of previous works and presents a case for 
use of predictive algorithms in dynamic resource allocation in heterogeneous GPU clusters to achieve enhanced 
utilization and discussed known issues relatable to resource allocation infrastructures within GPU clusters 
and proposes a multilayered deep network predictive algorithm for use in dynamic resource allocation in 
heterogeneous GPU clusters to achieve enhanced utilization.  

# [1] Introduction 
According to IBM, 90% of the world’s data has been created in the last two years and evidence suggests data  
creation is not slowing but increasing exponentially. Moreover, this increase in data creation and big data 
processing systems requirements of high performance in memory computing, has led to the development and use 
of advanced distributed computing techniques such as distributed-parallel computing, cloud computing, 
clustering, and high-performance computing integrated with heterogeneous computing infrastructures consisting 
of layered virtualization over multiple variations of concurrent CPU and GPU environments [33]. 

<img width="600" height="400" alt="image" src="https://github.com/deep-model/Data_Center_Utilization_of_Heterogenous_GPU_Clusters/blob/main/Distributed%20GPU%20Cluster.jpg" /> 

In order to process big data at the rates and volumes mentioned, not only have new techniques been developed 
such as Spark, Hadoop, and MapReduce, but advances in distributed cloud computing and clustering have led to a 
hyperbolic expansion of data centers around the globe.  Combined with parallel computing architectures of 
GPUs, cloud computing infrastructures have contributed to accelerated training and inference often expected of 
deep model networks. This robust parallelization for tensor processing and neural networks presents GPU 
clusters as a preferred processing solution for many supervised and unsupervised AI/ML tasks. A common 
framework for distributed clusters consists of varying models of GPUs and CPUs to form heterogeneous GPU 
clusters. 

This offers flexible allocation and utilization of a diverse range of tasks and offers flexible system 
performance and scalability of existing systems and infrastructure. However, this new challenges are 
presented in heterogeneous GPU clusters such as scheduling resources, workload balancing, and under
utilization leading to decreased performance, suboptimal efficiency, and reduced realized availability with long 
queuing latency. Moreover, an increase in power usage for GPU clusters is realized adding unnecessary cost for both 
the cloud service provider and customer [12]. 


