# Deep-learning-based acceleration of MRI for radiotherapy planning of pediatric patients with brain tumors

DeepMRIRec is a deep learning based pipeline for RT-coil specific MRI reconstruction. DeepMRIRec accelarate MRI acquisition by 4 times and produce sharp and trustworthy images to meet demands of mission critical applications. The details of the methods can be found in our manuscript. If you want to use our methods please follow the steps from "scripts/DeepMRIRec" jupyter notebook. 

![MRI Reconstruction](misc/recout.jpg?raw=true "MRI Reconstruction")

## Hardware and software requirements for model inference and training
1. Supported GPU: NVIDIA DGX/ A100 GPU with 80 GB Memory
2. Nvidia Driver 450.80.02
3. CUDA Version: 11.0
4. Python 3.6+
5. Tensorflow, keras, imgaug, scipy
6. LFS git


## Training and Evaluation

If you want to train our network on your data please follow the notebook located in "scripts" folder. We have also shared our network weights (see "network_weights" folder) in case if you want to use them for transfer learning. The weight files are described below.

X 12 original coils
P  2 loop coils
Q  2 virtual coils
Q3 3 virtual coils
Q4 4 virtual coils

## Contacts
Please feel free to contact us (salam@stjude.org,kkhairy@stjude.org) if you have questions or concerns
