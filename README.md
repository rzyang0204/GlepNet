# [GlepNet](https://ruizhiyang0204.github.io/GlepNet/)
### Learning Robust Global-Local Representation from EEG for Neural Epilepsy Detection
#### *by: Xinliang Zhou,  Chenyu Liu, Ruizhi Yang,   Liangwei Zhang,  Liming Zhai, Ziyu Jia, and Yang Liu*
This work has been accepted for publication in [IEEE Transactions on Artificial Intelligence (TAI).](https://www.researchgate.net/publication/379323759_Learning_Robust_Global-Local_Representation_from_EEG_for_Neural_Epilepsy_Detection)

## Abstract

[//]: # (![GlepNet Architecture]&#40;docs/Learning Robust Global-Local Representation from EEG for Neural Epilepsy Detection/Architecture.png&#41;)
<p align = "center">    
<img  src="docs/Learning Robust Global-Local Representation from EEG for Neural Epilepsy Detection/Architecture.png" width="600" />
</p>

Epilepsy is a life-threatening and challenging neurological disorder, and applying electroencephalogram (EEG) is a commonly used clinical approach 
for its detection. Neuropsychological research indicates that epilepsy seizure is highly associated with distinct ranges of temporal EEG patterns. 
Although previous attempts to automatically detect epilepsy have achieved high classification performance, one crucial challenge still remains: 
How to effectively learn the robust global-local representation associated with epilepsy in the signals? To address the above challenge, 
we propose GlepNet, a novel architecture for automatic EEG epilepsy detection. We interleave temporal convolution model together with the muti-head 
attention mechanism within the GlepNet's encoder blocks to jointly capture the interlaced epilepsy seizure local and global features in EEG signals. 
Meanwhile, the interpretable method, Grad-CAM, is applied to visually confirm that the GlepNet acquires the ability to accord significant weight to 
EEG segments containing epileptiform abnormalities like spike-wave complexes. Specifically, the Grad-CAM heatmaps are generated by backpropagating 
the gradients from the encoder blocks to highlight the epilepsy seizure-related parts. Extensive experiments show the superiority of the GlepNet over 
state-of-the-art methods on multiple EEG epilepsy datasets.

## Requirmenets
In processing... We will release and update soon.


## Citation

```
@article{emadeldeen_attnSleep,
  author={...},
  journal={...}, 
  title={...}, 
  year={...},
  volume={...},
  pages={...},
  doi={...}
}
```


## Contact
Xinliang Zhou 
School of Computer Science and Engineering (SCSE)   
Nanyang Technological University, Singapore   
Email: xinliang001{at}e.ntu.edu.sg