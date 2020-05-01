### OpenCL [<sup>[1]</sup>](#wiki-opencl)
The fact that OpenCL allows workloads to be shared by CPU and GPU, 
executing the same programs, means that programmers can exploit both 
by dividing work among the devices [<sup>[2]</sup>](#survey_hete_com).
This leads to the problem of deciding how to partition the work, because 
the relative speeds of operations differ among the devices. Machine learning 
has been suggested to solve this problem: Grewe and O'Boyle describe a 
system of support-vector machines trained on compile-time features of 
program that can decide the device partitioning problem statically, without 
actually running the programs to measure their performance[<sup>[3]</sup>](#2011_tp).


### 参考

<div id="wiki-opencl"></div>
- [1] [Wikipedia] https://en.wikipedia.org/wiki/OpenCL
<div id="survey_hete_com"></div>
- [2] A Survey of CPU-GPU Heterogeneous Computing Techniques, 
ACM Computing Surveys, 2015.
<div id="2011_tp"></div>
- [3] Grewe, Dominik; O'Boyle, Michael F. P. (2011). 
A Static Task Partitioning Approach for Heterogeneous Systems Using OpenCL. 
Proc. Int'l Conf. on Compiler Construction. doi:10.1007/978-3-642-19861-8_16
