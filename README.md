# Automatic Localization and Quantitative Segmentation of CCC & CV in Fetal Brain Ultrasound

This repository presents the research outcomes from:

> **"A method framework of automatic localization and quantitative segmentation for the cavum septum pellucidum complex and the cerebellar vermis in fetal brain ultrasound images"**  
> *Qifeng Wang et al., Quantitative Imaging in Medicine and Surgery (QIMS), 2023*  
> DOI: [10.21037/qims-22-1242](https://dx.doi.org/10.21037/qims-22-1242)

---

## Overview

Our framework addresses the challenge of **automated localization and segmentation** of the:
- **Corpus Callosum–Cavum Septum Pellucidum Complex (CCSP)**  
- **Cerebellar Vermis (CV)**  

in **fetal brain mid-sagittal ultrasound images (FBMUIs)**, enabling efficient prenatal CNS anomaly detection.

![Framework](media/method_overview.png)

---

## Highlights
- **5-step automated pipeline**:  
  1. Average Template Generation (VAE)  
  2. CCSP Localization  
  3. CCSP Contour Segmentation  
  4. CV Localization (guided by CCSP)  
  5. CV Contour Segmentation  

- **Dataset**: 140 FBMUIs (20–28 weeks GA), annotated by five senior sonographers.  
- **Validated clinically** at Shengjing Hospital, China Medical University.

---

## Demonstrations

### Method and Results Video
[![Watch the demo](media/results_demo.gif)](media/demo_video.mp4)

- Full process: **Localization → Contour Segmentation → Quantification**  
- Includes **comparison with active contour baselines** (SNAKE, DRLSE, Chan-Vese, etc.)

---

## Publication
If you use this work or wish to collaborate, please cite:
Wang Q, Pei J, Ouyang J, Chen Y, Pu J, Humayun A, Zhao D, Liu B.
A method framework of automatic localization and quantitative segmentation for the cavum septum pellucidum complex and the cerebellar vermis in fetal brain ultrasound images.
Quant Imaging Med Surg. 2023;13(9):6059–6088.
doi:10.21037/qims-22-1242

[Read the paper (PDF)](docs/Wang2023_QIMS.pdf)

---

## Contact
For **data requests, academic collaborations, or presentation materials**:  
- **Email**: [wqf970702@mail.dlut.edu.cn](mailto:wqf970702@mail.dlut.edu.cn)  
- **ResearchGate**: [Qifeng Wang](https://www.researchgate.net/profile/Qifeng-Wang-9?ev=hdr_xprf)
