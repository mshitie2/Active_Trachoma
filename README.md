# Adaptive Feature Selection for Active Trachoma Image Classification
<img src=" https://github.com/mshitie2/main/FS_model3.png" width="1000" height="600">

[[Paper]](https://authors.elsevier.com/sd/article/S0950-7051(24)00399-X)

## Abstract
Trachoma is a neglected tropical eye disease caused by ocular strains of 
Chlamydia trachomatis, which affects millions of people worldwide. 
To examine the eye for signs of active trachoma, healthcare providers typically 
look for clusters of five or more follicles on the conjunctiva of the upper eyelid 
for the follicular inflammatory trachoma stage. However, it is also possible to find individual 
follicles scattered throughout the conjunctiva, particularly in mild or early-stage trachoma cases.
Additionally, the datasets are photographic images collected in the field that can be high-dimensional 
and may contain large amounts of redundant information. We propose integrating novel attention-based 
feature extraction and feature selection techniques to address these challenges. First, we present 
the Lambda layer within the Convolutional Block Attention Module (L-CBAM) to normalize attention weights 
and improve the feature extraction process. Second, we introduce an adaptive mechanism, Adaptive Beta Hill Climbing (AβHC) 
with Social Ski-Driver (SSD), which adjusts the exploration-exploitation trade-off during the search process, allowing
for better exploration of the search space and more efficient convergence toward an optimal feature subset.
We then use the multilayer perceptron (MLP) classifier to produce final classification results using selected subsets. 
We evaluated the proposed approach on active trachoma inverted eyelid images and obtained accuracy scores of 93.3% with only 19.7% of
the selected features, surpassing many of the algorithms used for comparison. Our proposed method has demonstrated excellent 
performance compared to recent works utilizing the same datasets.


## Journal Paper
If you find our proposed methodology useful, please consider citing it
```
@article{KNOSYS_111764,
  title={Adaptive Feature Selection for Active Trachoma Image Classification},
  
  author={Mulugeta Shitie Zewudie, Shengwu Xiong, Xiaohan Yu, Xiaoyu Wu and Moges Ahmed Mehameda},
  
  journal={Knowledge-Based Systems},
  
  year={2024},
  
  publisher={Elsevier}
}
```
## Installation
1. Make sure you have python3 setup on your system
2. Clone the repo
```
git clone https://github.com/subhankar01/covidfs-aihc
```
3. Install requirements
```
pip install -r requirements.txt
```
## Contact
In case of doubt or further collaboration, feel free to email us ! 😊
- [Xiaohan Yu (xiaohan.yu@griffith.edu.au) ](mailto:xiaohan.yu@griffith.edu.au)
- [Mulugeta Shitie Zewudie (mshitie@whut.edu.cn)](mailto:mshitie@whut.edu.cn)

