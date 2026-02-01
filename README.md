# Selective Noise Suppression and Discriminative Mutual Interaction for Robust Audio-Visual Segmentation

[![IEEE TMM](https://img.shields.io/badge/IEEE%20TMM-Accepted-success)](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=6046)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> **Authors:** Kai Peng\#, Yunzhe Shen\#, Miao Zhang*, Leiye Liu, Yidong Han, Wei Ji, Jingjing Li, Yongri Piao*, and Huchuan Lu.
>
> **Affiliations:** > 1. Dalian University of Technology, China
> 2. Yale University, USA
> 3. University of Alberta, Canada
>
> *(\# Equal Contribution, * Corresponding Author)*

## 📢 News
- **[2026-02-01]** Our paper **SDNet** has been accepted by **IEEE Transactions on Multimedia (TMM)**! 🎉
- **[Coming Soon]** The official code, pre-trained weights, and datasets configurations will be released here shortly. Please stay tuned!

## 📖 Abstract
The ability to capture and segment sounding objects in dynamic visual scenes is crucial for the development of Audio-Visual Segmentation (AVS) tasks. While significant progress has been made in this area, the interaction between audio and visual modalities still requires further exploration. 

In this work, we aim to answer the following questions: 
1. How can a model effectively suppress audio noise while enhancing relevant audio information? 
2. How can we achieve discriminative interaction between the audio and visual modalities? 

To this end, we propose **SDNet**, equipped with the **Selective Noise-Resilient Processor (SNRP)** module and the **Discriminative Audio-Visual Mutual Fusion (DAMF)** strategy. The proposed SNRP mitigates audio noise interference by selectively emphasizing relevant auditory cues, while DAMF ensures more consistent audio-visual representations. Experimental results demonstrate that our proposed method achieves state-of-the-art performance on benchmark AVS datasets (S4, MS3, AVSS), especially in multi-source and complex scenes.

## 🏗️ Framework
*(The overall pipeline of the proposed SDNet, which includes SNRP and DAMF modules.)*

![Framework](structure.pdf) 
*(Note: Please upload your 'structure.pdf' or convert it to 'structure.png' and upload it to the repo for this image to display)*

## 🛠️ Usage
We are currently organizing the code and documentation. 
- [ ] Release inference code
- [ ] Release training scripts
- [ ] Release pre-trained models

**The full implementation will be available soon.**

## ✏️ Citation
If you find this work useful for your research, please cite:

```bibtex
@article{peng2026selective,
  title={Selective Noise Suppression and Discriminative Mutual Interaction for Robust Audio-Visual Segmentation},
  author={Peng, Kai and Shen, Yunzhe and Zhang, Miao and Liu, Leiye and Han, Yidong and Ji, Wei and Li, Jingjing and Piao, Yongri and Lu, Huchuan},
  journal={IEEE Transactions on Multimedia},
  year={2026},
  publisher={IEEE}
}
