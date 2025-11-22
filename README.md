[![License: GPL3.0](https://img.shields.io/badge/License-GPL3.0-yellow.svg)](https://opensource.org/licenses/GPL-3.0)
![Python](https://img.shields.io/badge/python-green.svg)
![GitHub stars](https://img.shields.io/github/stars/JeremyXSC/Med-Vision.svg?style=flat&label=Star)

# Med-Vision: Parameter-Efficient Fine-Tuning of LLM for Medical Report Generation
### [Suncheng Xiang](https://JeremyXSC.github.io/)
### [Shanghai Jiao Tong University](https://en.sjtu.edu.cn/)


## Overview
we propose a novel framework named Med-Vision that leverages multi-modal large models for automated polyp diagnosis report generation. In particular, we construct a multimodal dataset comprising colonoscopy images and expert diagnostic texts, fine-tune the Qwen3-VL-Instruct model using parameter-efficient methods and further optimize it with Direct Preference Optimization. Extensive experiments demonstrate that our method outperforms existing approaches on both automated metrics and clinical expert evaluations, significantly reducing computational requirements while maintaining high performance.

This AI agent should be used for research only. Please DO NOT distribute or use it for commercial purpose🔐. 

****

<img src='images/Med-Vision.png'/>

[**[Paper]**](https://arxiv.org/pdf/2109.10498.pdf)   [**[Video Sample]**](https://www.youtube.com/watch?v=toR_73U9yLs)   [**[Related Project]**](https://JeremyXSC.github.io/GPR/)   [**[Demo]**](https://modelscope.cn/studios/Zaoshangzhou/Med-Vision-AI-Agent/summary)  

</div> 

****
## :fire: NEWS :fire:
- [11/2025] **📣 Our 🚀Med-Vision AI Agent is publicly availble online.!**

****
## Table of Contents👀
- [Med-Vision Introduction](#Med-Vision Introduction)

****
## Med-Vision Introduction
The Med-Vision is a novel framework named Med-Vision that leverages multi-modal large models for automated polyp diagnosis report generation.
<br>


#### A weight of Med-Vision can be downloaded from the following links:<br>
* Microsoft OneDrive:
    * [Download Link](https://1drv.ms/f/c/f90b38354a7cfaf5/IgB0EI_2kJ22Qr71S4_L3mjOAY5i3IiYPxM47q93eM6OSQs?e=Tdcok2)
</div> 

## Citation
If you use our FineGPR dataset for your research, please cite our [Paper](https://dl.acm.org/doi/pdf/10.1145/3588441).
```
@article{xiang2023less,
  title={Less is more: Learning from synthetic data with fine-grained attributes for person re-identification},
  author={Xiang, Suncheng and Qian, Dahong and Guan, Mengyuan and Yan, Binjie and Liu, Ting and Fu, Yuzhuo and You, Guanjie},
  journal={ACM Transactions on Multimedia Computing, Communications and Applications},
  volume={19},
  number={5s},
  pages={1--20},
  year={2023},
  publisher={ACM New York, NY}
}
```
****

## Ethical Considerations
Our task and dataset were created with careful attention to ethical questions, which we encountered throughout our work. Access to our dataset will be provided for research purposes only and with restrictions on redistribution. Furthermore, we are very cautious of human-annotation procedure of large scale datasets to avoid the social and ethical implications. 
As for re-ID system, governments and officials must establish strict regulations to control the usage of this technology since it mainly relies on (not all) surveillance data. Motivated by this, we do not consider the datasets for developing non-research systems without further professional processing or augmentation.

****

## LICENSE
- The Med-Vision are made available for non-commercial purposes only.
- You will not, directly or indirectly, reproduce, use, or convey the FineGPR  dataset and FineGPR-C caption dataset or any Content, or any work product or data derived therefrom, for commercial purposes.

Permissions of this strong copyleft license (GNU General Public License v3.0) are conditioned on making available complete source code of licensed works and modifications, which include larger works using a licensed work, under the same license. Copyright and license notices must be preserved. Contributors provide an express grant of patent rights.

****

## Acknowledgements
This research was supported by the National Natural Science Foundation of China under Project (Grant No. 62301315). We would like to thank authors of Tianyu Zhou and Jingsheng Gao for his hard work on this work. They provide tremendous efforts in these dataset to advance the research in this field. We also appreciate [Zefang Yu](https://github.com/yuzefang96), [Mingye Xie](https://myronxie.github.io/) and [Guanjie You](https://github.com/YGJsGitHub) for insightful feedback and discussion.

****

For further questions and suggestions about our datasets and methods, please feel free to contact Suncheng Xiang:
xiangsuncheng17@sjtu.edu.cn.