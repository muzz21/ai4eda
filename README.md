# ai4eda
**A collection of design automation algorithms, methodologies, and tools for electronics/photonics, and emerging eda technologies**

Contributed by Yuan Wang.

## [Content](#content)

<table>
<tr><td colspan="2"><a href="#analog-circuit-optimization">1. analog circuit optimization</a></td></tr>
<tr>
    <td>&ensp;<a href="#simulation-based">1.1 simulation-based</a></td>
    <td>&ensp;<a href="#learning-based">1.2 learning-based</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#bayesian-optimization">1.3 bayesian optimization</a></td>
    <td>&ensp;<a href="#GNN">1.4 GNN</a></td>
</tr>
<tr><td colspan="2"><a href="#photonics">2. photonics</a></td></tr>
<tr><td colspan="2"><a href="#survey">3. survey</a></td></tr>
<tr><td colspan="2"><a href="#tools">4. tools</a></td></tr>
</table>


## [analog circuit optimization](#content)
### [simulation-based](#content)
1. **Two-Step RF IC Block Synthesis With Preoptimized Inductors and Full Layout Generation In-the-Loop.**  [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8356050)

    *Ricardo Martins, Nuno Lourenço,  Fábio Passos, Ricardo Póvoa.*

2. **Anaconda: simulation-based synthesis of analog circuits via stochastic pattern search.**  [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=848091)

    *R. Phelps, M. Krasnicki, R.A. Rutenbar, L.R. Carley, J.R. Hellums.*

3. **A new metaheuristc combining gradient models with NSGA-II to enhance analog IC synthesis.**  [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6557906)

    *F. Rocha, N. Lourenço, R. Póvoa, R. Martins, N. Horta.*

4. **Automated design of analog and high-frequency circuits.**  [book](https://linkspringer.53yu.com/)

    *B Liu, G Gielen, FV Fernández.*


### [learning-based](#content)
1. **AutoCkt: Deep Reinforcement Learning of Analog Circuit Designs.**  [paper](https://arxiv.org/pdf/2001.01808.pdf)

    *Keertana Settaluri, Ameer Haj-Ali, Qijing Huang, Kourosh Hakhamaneshi, Borivoje Nikolic.*

2. **GASPAD: A General and Efficient mm-Wave Integrated Circuit Synthesis Method Based on Surrogate Model Assisted Evolutionary Algorithm.**  [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6714475)

    *Bo Liu, Dixian Zhao, Patrick Reynaert, Georges G. E. Gielen.*

3. **Electric Analog Circuit Design with Hypernetworks and a Differential Simulator.**  [paper](https://arxiv.org/pdf/1911.03053.pdf)

    *Michael Rotman, Lior Wolf.*

4. **GCN-RL Circuit Designer: Transferable Transistor Sizing with Graph Neural Networks and Reinforcement Learning.**  [paper](https://arxiv.org/pdf/2005.00406.pdf)

    *Hanrui Wang, Kuan Wang, Jiacheng Yang, Linxiao Shen, Nan Sun, Hae-Seung Lee, Song Han.*

5. **Learning to Design Circuits.**  [paper](https://arxiv.org/pdf/1812.02734.pdf)

    *Hanrui Wang, Jiacheng Yang, Hae-Seung Lee, Song Han.*

6. **An Efficient Analog Circuit Sizing Method Based on Machine Learning Assisted Global Optimization.**  [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9434374)

    *Ahmet Faruk Budak, Miguel Gandara, Wei Shi, David Z. Pan, Nan Sun, Bo Liu.*

7. **Automated Design of Analog Circuits using Machine Learning Techniques.**  [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9601131)

    *S Devi, Gourav Tilwankar, Rajesh Zele.*

8. **Trust-Region Method with Deep Reinforcement Learning in Analog Design Space Exploration.**  [paper](https://arxiv.org/pdf/2009.13772.pdf)

    *Kai-En Yang, Chia-Yu Tsai, Hung-Hao Shen, Chen-Feng Chiang, Feng-Ming Tsai, Chung-An Wang, Yiju Ting, Chia-Shun Yeh, Chin-Tang Lai.*

9. **DNN-Opt: An RL Inspired Optimization for Analog Circuit Sizing using Deep Neural Networks.**  [paper](https://arxiv.org/pdf/2110.00211.pdf)

    *Ahmet F. Budak, Prateek Bhansali, Bo Liu, Nan Sun, David Z. Pan, Chandramouli V. Kashyap.*

10. **Using ANNs to Size Analog Integrated Circuits.**  [book](https://linkspringer.53yu.com/chapter/10.1007/978-3-030-35743-6_4)

    *João P. S. Rosa, Daniel J. D. Guerra, Nuno C. G. Horta, Ricardo M. F. Martins & Nuno C. C. Lourenço.*

11. **BagNet: Berkeley Analog Generator with Layout Optimizer Boosted with Deep Neural Networks.**  [paper](https://arxiv.org/pdf/1907.10515.pdf)

    *Kourosh Hakhamaneshi, Nick Werblun, Pieter Abbeel, Vladimir Stojanovic.*

12. **Transfer Learning with Bayesian Optimization-Aided Sampling for Efficient AMS Circuit Modeling.**  [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9256598)

    *Juzheng Liu, Mohsen Hassanpourghadi, Qiaochu Zhang, Shiyu Su, Mike Shuo-Wei Chen.*

13. **A Gaussian Process Surrogate Model Assisted Evolutionary Algorithm for Medium Scale Expensive Optimization Problems.**  [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6466380)

    *Bo Liu, Qingfu Zhang, Georges G. E. Gielen.*

14. **Automatic Selection of Process Corner Simulations for Faster Design Verification.**  [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8023765)

    *Michael Shoniker, Oleg Oleynikov, Bruce F. Cockburn, Jie Han, Manish Rana, Witold Pedrycz.*

15. **Minimizing the Number of Process Corner Simulations during Design Verification.**  [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7092399)

    *Michael Shoniker, Bruce F. Cockburn, Jie Han, Witold Pedrycz.*


16. **Analog circuit topological feature extraction with unsupervised learning of new sub-structures.**  [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7459552)

    *Hao Li, Fanshu Jiao, Alex Doboli.*

17. **Late Breaking Results: An Efficient Learning-based Approach for Performance Exploration on Analog and RF Circuit Synthesis.**  [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8806800)

    *Po-Cheng Pan, Chien-Chia Huang, Hung-Ming Chen.*

18. **A Circuit Attention Network-Based Actor-Critic Learning Approach to Robust Analog Transistor Sizing.**  [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9531156)

    *Yaguang Li, Yishuang Lin, Meghna Madhusudan, Arvind Sharma, Sachin Sapatnekar, Ramesh Harjani, Jiang Hu.*

19. **Prioritized Reinforcement Learning for Analog Circuit Optimization With Design Knowledge.**  [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9586189)

    *N.S. Karthik Somayaji, Hanbin Hu, Peng Li.*

20. **Fast Variation-aware Circuit Sizing Approach for Analog Design with ML-Assisted Evolutionary Algorithm.**  [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9712559)

    *Ling-Yen Song, Tung-Chieh Kuo, Ming-Hung Wang, Chien-Nan Jimmy Liu, Juinn-Dar Huang.*

21. **CEPA: CNN-based Early Performance Assertion Scheme for Analog and Mixed-Signal Circuit Simulation.**  [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9256532)

    *Qiaochu Zhang, Shiyu Su, Juzheng Liu, Mike Shuo-Wei Chen.*

22. **A Fast and Accurate Middle End of Line Parasitic Capacitance Extraction for MOSFET and FinFET Technologies Using Machine Learning.**  [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9712514)

    *Mohamed Saleh Abouelyazid, Sherif Hammouda, Yehea Ismail.*

23. **Automatic analog schematic diagram generation based on building block classification and reinforcement learning** [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9900093)

    *Hsu, Hung-Yun and Lin, Mark Po-Hung*

### [bayesian optimization](#content)

1. **An Efficient Batch Constrained Bayesian Optimization Approach for Analog Circuit Synthesis via Multi-objective Acquisition Ensemble.**  [paper](https://arxiv.org/pdf/2106.15412.pdf)

    *Shuhan Zhang, Fan Yang, Changhao Yan, Dian Zhou, Xuan Zeng.*

2. **An Efficient Bayesian Optimization Approach for Automated Optimization of Analog Circuits.**  [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8116661)

    *Wenlong Lyu, Pan Xue, Fan Yang, Changhao Yan, Zhiliang Hong, Xuan Zeng, Dian Zhou.*

3. **Batch Bayesian Optimization via Multi-objective Acquisition Ensemble for Automated Analog Circuit Design.**  [paper](http://proceedings.mlr.press/v80/lyu18a/lyu18a.pdf)

    *Wenlong Lyu, Fan Yang, Changhao Yan, Dian Zhou, Xuan Zeng.*

4. **High-Dimensional Bayesian Optimization for Analog Integrated Circuit Sizing Based on Dropout and gm/ID Methodology.**  [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9698107)

    *Chen Chen, Hongyi Wang, Xinyue Song, Feng Liang, Kaikai Wu, Tao Tao.*

5. **LinEasyBO: Scalable Bayesian Optimization Approach for Analog Circuit Synthesis via One-Dimensional Subspaces.**  [paper](https://arxiv.org/pdf/2109.00617.pdf)

    *Shuhan Zhang, Fan Yang, Changhao Yan, Dian Zhou, Xuan Zeng.*

6. **Multi-objective Bayesian Optimization for Analog/RF Circuit Synthesis.**  [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8465872)

    *Wenlong Lyu, Fan Yang, Changhao Yan, Dian Zhou, Xuan Zeng.*

7. **A Novel and Efficient Bayesian Optimization Approach for Analog Designs with Multi-Testbench.**  [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9712590)

    *Jingyao Zhao, Changhao Yan, Zhaori Bi, Fan Yang, Xuan Zeng, Dian Zhou.*



### [GNN](#content)

1. **Pretraining Graph Neural Networks for few-shot Analog Circuit Modeling and Design.**  [paper](https://arxiv.org/pdf/2203.15913.pdf)

    *Kourosh Hakhamaneshi, Marcel Nassar, Mariano Phielipp, Pieter Abbeel, Vladimir Stojanović.*

2. **ParaGraph: Layout Parasitics and Device Parameter Prediction using Graph Neural Networks.**  [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9218515)

    *Haoxing Ren, George F. Kokai, Walker J. Turner, Ting-Sheng Ku.*

3. **GANA: Graph Convolutional Network Based Automated Netlist Annotation for Analog Circuits.**  [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9116329)

    *Kishor Kunal, Tonmoy Dhar, Meghna Madhusudan, Jitesh Poojary, Arvind Sharma, Wenbin Xu, Steven M. Burns, Jiang Hu, Ramesh Harjani, Sachin S. Sapatnekar.*

4. **Layout Symmetry Annotation for Analog Circuits with Graph Neural Networks.**  [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9371557)

    *Xiaohan Gao, Chenhui Deng, Mingjie Liu, Zhiru Zhang, David Z. Pan, Yibo Lin.*

5. **A general approach for identifying hierarchical symmetry constraints for analog circuit layout.**  [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9256812)

    *Kishor Kunal, Jitesh Poojary, Tonmoy Dhar, Meghna Madhusudan, Ramesh Harjani, Sachin S. Sapatnekar.*

6. **A Customized Graph Neural Network Model for Guiding Analog IC Placement.**  [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9256781)

    *Yaguang Li, Yishuang Lin, Meghna Madhusudan, Arvind Sharma, Wenbin Xu, Sachin S. Sapatnekar, Ramesh Harjani, Jiang Hu.*

7. **ASIC Circuit Netlist Recognition Using Graph Neural Network.**  [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9617311)

    *Xuenong Hong, Tong Lin, Yiqiong Shi, Bah Hwee Gwee.*

8. **Machine Learning Techniques in Analog Layout Automation.**  [paper](https://dl.acm.org/doi/abs/10.1145/3439706.3446896)

    *T Dhar, K Kunal, Y Li, Y Lin, M Madhusudan.*

9. **Intelligent and Interactive Analog Layout Design Automation.**  [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9963217)

    *Yibo Lin, Xiaohan Gao, Haoyi Zhang, Runsheng Wang, Ru Huang.*

10. **Bringing Structure into Analog IC Placement with Relational Graph Convolutional Networks.**  [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9547917)

    *Antonio Gusmao, Nuno Horta, Nuno Lourenco, Ricardo Martins.*

11. **Universal Symmetry Constraint Extraction for Analog and Mixed-Signal Circuits with Graph Neural Networks.**  [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9586211)

    *Hao Chen, Keren Zhu, Mingjie Liu, Xiyuan Tang, Nan Sun, David Z. Pan.*

12. **S3DET: Detecting System Symmetry Constraints for Analog Circuits with Graph Similarity.**  [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9045109)

    *Mingjie Liu, Wuxi Li, Keren Zhu, Biying Xu, Yibo Lin, Linxiao Shen, Xiyuan Tang, Nan Sun, David Z. Pan.*

13. **Parasitic-Aware Analog Circuit Sizing with Graph Neural Networks and Bayesian Optimization.**  [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9474253)

    *Mingjie Liu, Walker J. Turner, George F. Kokai, Brucek Khailany, David Z. Pan, Haoxing Ren.*

14. **Fast Thermal Analysis for Chiplet Design based on Graph Convolution Networks.**  [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9712583)

    *Liang Chen, Wentian Jin, Sheldon X.-D. Tan.*

15. **Program-to-Circuit: Exploiting GNNs for Program Representation and Circuit Translation.**  [paper](https://arxiv.org/pdf/2109.06265.pdf)

    *Nan Wu, Huake He, Yuan Xie, Pan Li, Cong Hao.*

16. **Floorplanning with graph attention.**  [paper](https://dl.acm.org/doi/abs/10.1145/3489517.3530484)

    *Y Liu, Z Ju, Z Li, M Dong, H Zhou, J Wang.*

17. **Net2: A Graph Attention Network Method Customized for Pre-Placement Net Length Estimation.**  [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9371657)

    *Zhiyao Xie, Rongjian Liang, Xiaoqing Xu, Jiang Hu, Yixiao Duan, Yiran Chen.*

18. **Deep H-GCN: Fast Analog IC Aging-Induced Degradation Estimation.**  [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9521579)

    *Tinghuan Chen, Qi Sun, Canhui Zhan, Changze Liu, Huatao Yu, Bei Yu.*

19. **Deep H-GCN: Fast Analog IC Aging-Induced Degradation Estimation.**  [paper](https://guozz.cn/publication/mltimerdac-22/mltimerdac-22.pdf)

    *Z Guo, M Liu, J Gu, S Zhang, DZ Pan, Y Lin.*

20. **High-Level Synthesis Performance Prediction using GNNs: Benchmarking, Modeling, and Advancing.**  [paper](https://arxiv.org/pdf/2201.06848.pdf)

    *Nan Wu, Hang Yang, Yuan Xie, Pan Li, Cong Hao.*

21. **Comprehensive Mapping of Continuous/Switching Circuits in CCM and DCM to Machine Learning Domain using Homogeneous Graph Neural Networks** [paper](http://xn--xiaosenhttps-ox5t//ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10006651)

    *Khamis, Ahmed K and Agamy, Mohammed*

22. **Fully automated analog sub-circuit clustering with graph convolutional neural networks** [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9116513)

    *Settaluri, Keertana and Fallon, Elias*

23. **Graph learning-based arithmetic block identification** [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9643581)

    *He, Zhuolun and Wang, Ziyi and Bail, Chen and Yang, Haoyu and Yu, Bei*


## [photonics](#content)

1. **NeurOLight: A Physics-Agnostic Neural Operator Enabling Parametric Photonic Device Simulation.**  [paper](https://arxiv.org/pdf/2209.10098.pdf)

    *Jiaqi Gu, Zhengqi Gao, Chenghao Feng, Hanqing Zhu, Ray T. Chen, Duane S. Boning, David Z. Pan.*


## [survey](#content)

1. **Machine Learning for Electronic Design Automation: A Survey.**  [paper](https://arxiv.org/pdf/2102.03357.pdf)

    *Guyue Huang, Jingbo Hu, Yifan He, Jialong Liu, Mingyuan Ma, Zhaoyang Shen, Juejian Wu, Yuanfan Xu, Hengrui Zhang, Kai Zhong, Xuefei Ning, Yuzhe Ma, Haoyu Yang, Bei Yu, Huazhong Yang, Yu Wang.*

2. **MLCAD: A Survey of Research in Machine Learning for CAD Keynote Paper.**  [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9598835)

    *Martin Rapp, Hussam Amrouch, Yibo Lin, Bei Yu, David Z. Pan, Marilyn Wolf, Jörg Henkel.*

3. **Reinforcement Learning for Electronic Design Automation: Case Studies and Perspectives: (Invited Paper).**  [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9712578)

    *Ahmet F. Budak, Zixuan Jiang, Keren Zhu, Azalia Mirhoseini, Anna Goldie, David Z. Pan.*

4. **Machine Learning in Nanometer AMS Design-for-Reliability : (Invited Paper).**  [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9620496)

    *Tinghuan Chen, Qi Sun, Bei Yu.*

5. **Understanding Graphs in EDA: From Shallow to Deep Learning.**  [paper](https://dl.acm.org/doi/abs/10.1145/3372780.3378173)

    *Y Ma, Z He, W Li, L Zhang, B Yu.*

6. **Applications of artificial intelligence on the modeling and optimization for analog and mixed-signal circuits: A review** [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9383813)

    *Fayazi, Morteza and Colter, Zachary and Afshari, Ehsan and Dreslinski, Ronald*


## [tools](#content)

1. **MAGICAL: Toward Fully Automated Analog IC Layout Leveraging Human and Machine Intelligence.**  [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8942060)

    *Biying Xu, Keren Zhu, Mingjie Liu, Yibo Lin, Shaolan Li, Xiyuan Tang, Nan Sun, David Z. Pan.*

2. **The ALIGN Open-Source Analog Layout Generator: v1.0 and Beyond (Invited talk).**  [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9256499)

    *Tonmoy Dhar, Kishor Kunal, Yaguang Li, Yishuang Lin, Meghna Madhusudan, Jitesh Poojary, Arvind K. Sharma, Steven M. Burns, Ramesh Harjani, Jiang Hu, Parijat Mukherjee, Soner Yaldiz, Sachin S. Sapatnekar.*

3. **https://github.com/ALIGN-analoglayout/ALIGN-public**

4. **https://github.com/ucb-art/BAG_framework**

5. **https://github.com/PySpice-org/PySpice**