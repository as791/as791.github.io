## Portfolio
### Experience
#### Research Intern, TCS Research & Innovation 
##### Team Member, Embedded Systems and Robotics
###### Kolkata, May 2020 - Jul 2020
*3D Face Reconstruction*
- Worked in a developement of the end-to-end pipeline to reconstruct 3D Face Meshes using 2D images.
- Worked with [SFM model and eos C++ library](https://github.com/patrikhuber/eos/). Used them to an advantage with [ARAP-Surface Modeling](https://igl.ethz.ch/projects/ARAP/) to improve the leap areas of the Reconstructed Face Mesh. 
- Developed a python binding for the same proposed methodology and made user friendly python script to optimize and improve the selected leap areas.
- Achieved an improvement of **~20-50%** in reprojection error (case to case basis) for the selected leap areas.

---
#### Summer Research Fellow, IIIT Bangalore 
##### Guide: Prof. Uttam Kumar
###### Bangalore, May 2019 - Jul 2019                                 
*Evaluation of different machine learning algorithms for multi-spectral satellite image classification.*
- Worked with the multi-spectral satellite data of Bangalore captured during March 2018 by **Landsat 8 OLI**.
- Used GRASS GIS, free open-source software suite by OSGeo for visualisation for data annotation and map productions. Used scikit-learn and keras to build the classifiers. 
- Built 7 different classifiers and did their **comparative evaluation based on their user’s, producer’s, overall accuracy and kappa statistics.** 
- Also, built an ensemble classifier using set of three models to get best error-corrected classified map. Achieved best classification map with overall accuracy of **96.06%**.
- Analyzed **% land cover** use for best classified map to conclude towards the development of city policies for "Smart City" goals.

---
### Projects
[Multimodal Brain Tumor Segmentation](/Multimodal-Brain-Tumor-Segmentation)
- Segmentation of gliomas in pre-operative MRI scans. Used the provided clinically-acquired training data to produce segmentation labels.
- Pre-processed the provided clinically-acquired training data and applied simple **U-Net** as semantic segmentation model and **Dice Coefficient** as metrics for evaluation. Used Keras 
as framework.
- Achieved dice coefficient score of **0.9950** for lower grade glioma (LGG) and **0.9814 (average)** for glioblastoma (GBM/HGG).

---
[Adversarial Example Attack and Defense](/Adversarial-Example-Attack-and-Defense)
- Implemented three adversarial example attacks and one defense using *MNIST* dataset using PyTorch as framework.
- Achieved **~70% reduction** in test accuracy during the attacks, namely **FGSM, I-FGSM and MI-FGSM**.
- Used **Defensive Distillation** method as countermeasure to these attacks and achieved with only **~2% reduction** in test accuracy during the attacks.

---
[Generation of Adversarial Examples using DCGAN (Pokemon Dataset)](/Adversarial-Examples-of-Pokemon)
- Implemented **DC-GAN** using PyTorch as framework and applied it on Pokemon dataset fetched from kaggle.
- Achieved Discriminator to get fooled with the created adversarial examples with **99.96% accuracy (Training)**.

---
[Fundamental Brain Wave Extractor](/Fundamental-Brain-Waves-Extractor)
- Brainwaves can then be categorized based on their level of activity or frequency. There are five fundamental brain waves, Gamma, Beta, Alpha, Theta and Delta wave.
- Implemented a **Multi-Band Filtering Design System** using **MATLAB** which can be used to extract these five fundamental brain waves. 
- Filter Design is based on **Chebyshev Type-I approximation (analog)**, used **Bilinear Transformation** to convert analog filter to digital filter.

---
[Dog vs Cat Classification](https://www.kaggle.com/arya791/kernel6fb4bf1ec6)
- Classification between dog and cat. Used the Dogs-vs-Cats (redux) dataset from kaggle competition.
- Designed own model using Keras, achieved **F1 score of 91.50% and Log loss of 2.97 on the test data**. 

---
[Devanagari character recognition](https://github.com/as791/Devanagari-character-recognition)
- Character Recognition of the Devanagri, **58** different classes to classify.
- Built CNN using Keras, achieved **99.69% of test accuracy.**

---
### Technical Profile
- **Programming Languages** : C, C++, Python
- **Web Applications** : Jupyter Notebook, Google Colaboratory, Kaggle Kernel
- **Software Suites** : MeshLab, GRASS GIS, MATLAB & Simulink, Vivado
- **Frameworks and Libraries** : PyTorch, Tensorflow, Keras, Scikit-Learn, Scipy, OpenCV, Ceres Solver, Pandas, Matplolib
- **Simulation Tools** : Logisim, PSpice
- **Hardware Tools** : Arduino (Uno,Due), Basys3, Intel 8085
