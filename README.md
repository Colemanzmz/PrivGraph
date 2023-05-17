# PrivGraph
Implementation of PrivGraph
## Requirements


```
numpy >= 1.20.1
pandas >= 1.2.4
networkx >= 2.5
scikit-learn >= 0.24.1
python-louvain >= 0.15
python >= 3.8
```

## Contents

The project contains 3 folders and 6 files.

1. data (folder): All datasets are in this folder.           
   数据（文件夹）：所有数据集都在此文件夹中。
3. comm (folder): This folder is used for community discovery. 
   comm（文件夹）：此文件夹用于社区发现。
5. result (folder): This folder is used to store the results and contains four examples of synthetic graphs.
   result（文件夹）：此文件夹用于存储结果，包含四个合成图的示例。
7. main.py (file): The file is used to obtain the results of PrivGraph for End-to-End experiments.
   main.py（file）：该文件用于获得端到端实验的PrivGraph结果。
9. main_vary_N.py (file): The file is used to obtain the results for different number of nodes.
   main_vary_N.py（文件）：该文件用于获得不同数量节点的结果。
11. main_vary_eps.py (file): The file is used to obtain the results for different privacy budget allocations.
    main_vary_eps.py（文件）：该文件用于获得不同隐私预算分配的结果。
13. main_vary_t.py (file): The file is used to obtain the results for different resolution parameters.
    main_vary_t.py（文件）：该文件用于获得不同分辨率参数的结果。
15. IM_spread.py (file): The file is used to obtain the results of influence maximization.
    IM_spread.py（文件）：该文件用于获得影响力最大化的结果。
17. utils.py (file): The file includes some functions that are needed for other files.
    utils.py（文件）：该文件包括其他文件所需的一些函数。
The project contains 3 folders and 6 files.
该项目包含3个文件夹和6个文件。



## Run


```
###### Example 1: End to End ######
python main.py

###### Example 2: Impact of the number of nodes ######
python main_vary_N.py

###### Example 3: Impact of the privacy budget allocation ######
python main_vary_eps.py

###### Example 4: Impact of the resolution parameter ######
python main_vary_t.py

###### Example 5: Influence Maximization ######
python IM_spread.py
```

## Citation

```
 @inproceedings{YZDCCS23,
    author = {Quan Yuan and Zhikun Zhang and Linkang Du and Min Chen and Peng Cheng and Mingyang Sun},
    title = {{PrivGraph: Differentially Private Graph Data Publication by Exploiting Community Information}},
    booktitle = {{USENIX Security}},
    publisher = {},
    year = {2023},
}
```
