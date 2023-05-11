# ml_project - hyperparameter tuning resnet50 with breast cancer images

We trained ResNet50 models on hundreds of thousands of IDC breast cancer images to determine whether images contained cancer. These images were small patches from 152 patients, with the goal of having a model identify individual patches so that the oncologist can make a conclusion as to how to diagnose based on number of patches containing cancer.

![image0](https://github.com/MasterOoknaan/ml_project/blob/main/cancer.png)

Meant to run in Google Colab using GPU

Link to images.zip - https://drive.google.com/file/d/1refOE8uHMLcPHf3RQQAuGiWhCPlApnnX/view?usp=sharing
Store images.zip in Google Drive - 'drive/data/images.zip'

Initial Model

![image1](https://github.com/MasterOoknaan/ml_project/blob/main/old_graphs.png)

Hyperparameter tuned model

![image2](https://github.com/MasterOoknaan/ml_project/blob/main/hyperparam_graphs.png)

Observations - Barely any difference between initial model and hyperparameter tuned model. Both follow same pattern for loss and accuracy.