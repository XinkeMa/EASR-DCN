# EASR-DCN: Deformable Medical Image Registration with Effective Anatomical Structure Representation and Divide-and-Conquer Network

[Note!!]** The [pytorch](https://github.com/XinkeMa/EASR-DCN) version will be released soon and made publicly accessible! **

We propose a weakly-supervised ROI-based registration approach named EASR-DCN. Our method represents medical images through effective ROIs and achieves independent alignment of these ROIs without requiring labels. Specifically, we first used a Gaussian mixture model for intensity analysis to represent images using multiple effective ROIs with distinct intensities. Furthermore, we propose a novel Divide-and-Conquer Network (DCN) that processes ROIs through separate channels to independently align their features. The resulting sub-deformation fields are seamlessly integrated to generate a comprehensive displacement vector field. 
Extensive experiments were performed on three MRI and one CT datasets to showcase the superior accuracy and deformation reduction efficacy of our EASR-DCN..


<p align="center"><img width="100%" src="fig/detil.png" /></p>

## Paper
This repository provides the official tensorflow implementation of EASR-DCN in the following papers:

**Deformable Medical Image Registration with Effective Anatomical Structure Representation and Divide-and-Conquer Network** <br/> 
[Xinke Ma](https://scholar.google.com.hk/citations?user=RT_DBEUAAAAJ&hl=zh-CN&oi=ao), Yongsheng Pan, Qingjie Zeng, Mengkang Lu, Bolysbek Murat Yerzhanuly, Bazargul Matkerim, and [Yong Xia*](https://jszy.nwpu.edu.cn/en/yongxia.html) <br/>
Northwestern Polytechnical University <br/>
IEEE Journal of Biomedical And Health Informatics ([J-BHI](https://www.embs.org/jbhi/)) <br/>
[Paper](https://arxiv.org/abs/2506.19222) | [Code](https://github.com/XinkeMa/EASR-DCN)

## Available implementation
- [pytorch/](https://github.com/XinkeMa/EASR-DCN)

## Citation
If you use EASR-DCN for your research, please cite our papers:
```
@article{ma2025deformable,
  title={Deformable Medical Image Registration with Effective Anatomical Structure Representation and Divide-and-Conquer Network},
  author={Ma, Xinke and Pan, Yongsheng and Zeng, Qingjie and Lu, Mengkang and Yerzhanuly, Bolysbek Murat and Matkerim, Bazargul and Xia, Yong},
  journal={arXiv preprint arXiv:2506.19222},
  year={2025}
}
```

## Acknowledgments

This work was supported in part by the National Key R&D Program of China (2022YFC2009903, 2022YFC2009900), the National Natural Science Foundation of China (Grants 62171377 and 92470101), the Fundamental Research Funds for the Central Universities (5000230376), and the Ningbo Clinical Research Center for Medical Imaging (2021L003; Open Project 2022LYKFZD06).
