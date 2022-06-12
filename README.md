# Term-Project
This repository is Term Project repository.
======================================================================================
- DEADLINE : 11:59pm, 12th June, 2022 </br>
- **Datasets : CIFAR-10** </br>
- **Basic model : ResNet-18** </br>

## **experiments** </br>
**1. resnet18_lr.ipynb </br>**
 - first learning rate : 0.1 </br>
 - **<span style="background-color: #F5B801">accuracy : 91.27%</span> </br>**

 - second learning rate: 0.001 </br>
 - **<span style="background-color: #F5B801">accuracy : 93.37% </span></br>**

**2. resnet18_da.ipynb </br>**
 - I Applied Data Augmentation to the training dataset.</br>
  1) RandomCrop()</br>
  2) RandomHorizontalFlip()</br>
  3) ColorJitter()</br>
  4) Normalize()</br>
 - **<span style="background-color: #F5B801">accuracy : 70.61% </span></br>**

 - I Applied Data Augmentation to the training dataset and test dataset.</br>
 - Apply the same as above.</br>
 - **<span style="background-color: #F5B801">accuracy : 86.90%</span></br>**

**3. pretrain_resnet18.ipynb </br>**
 - I used pretrained model resnet18.</br>
 - The classifier part was newly created.</br>
 - I used AutoAugment. </br>
 - **<span style="background-color: #F5B801">accuracy : 94.24% </span></br>**

**4. pretrain_resnet34.ipynb </br>**
 - I used pretrained model resnet34. </br>
 - The classifier part was newly created.</br>
 - I used AutoAugment. </br>
 - **<span style="background-color: #F5B801">accuracy : 95.34% </span></br>**

**5. pretrain_resnet50.ipynb </br>**
 - I used pretrained model resnet50. </br>
 - The classifier part was newly created.</br>
 - I used AutoAugment. </br>
 - **<span style="background-color: #F5B801">accuracy : 95.47% </span></br>**

**6. resnet_ensemble.ipynb </br>**
 - Experiment with stacking ensemble of the three pretrained models learned earlier. </br>
 - Stacking Ensemble is called an ensemble because it uses several models. </br>
 - The structure of this Stacking Ensemble is a form of learning by using the data predicted by each model again as a training set.</br>
 - **<span style="background-color: #F5B801">accuracy : 95.87% </span></br>**

**7. resnet_ensemble2.ipynb </br>**
 - I changed DataAugmentation part.</br>
 - **<span style="background-color: #F5B801">accuracy : 83.94% </span></br>**
