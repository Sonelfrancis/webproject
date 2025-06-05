# deep learning project
Glaucoma is a serious eye condition that can lead to vision loss if not diagnosed early.
Early detection of glaucoma using deep learning technique with high accuracy and high sensitivity is the need of the hour.
Early diagnosis and treatment are critical for managing glaucoma and preventing further vision loss. 
Efficient detection of glaucoma from fundus images remains crucial and a challenging task in nature with varying contrast and boundaries. 

As a result, there is a chance that expert systems will misclassify the data. As a way to reduce the misclassification rate, a methodology wherein a deep learning approach integrated with an evolutionary algorithm is proposed. 

Transfer learning is a machine learning technique that allows a model trained on one task to be applied to a different but related task without the need for significant additional training. 

In transfer learning we worked with models like ResNet152, VGG16, VGG19, MobileNet V2, Inception V3, DenseNet121 , MobileNet , ResNet50 V2, Inception_ResNet , Xception using Keras. And found that Xception model is giving high accuracy comparatively. 
The efficiency of this fully automated system is evaluated on public retinal fundus image database LAG.

LAG stands for Large-scale Attention-based Glaucoma Dataset. 
The LAG dataset is a collection of fundus images for glaucoma detection and analysis. 
The LAG dataset can be used for image classification, anomaly detection, and semantic segmentation.
It contains 4854 images. There is train and test folder in the LAG dataset. Train folder consists of Normal 2514 and  Glaucoma 1369. Test folder consists of Normal 629 and Glaucoma 342.
Each images are in the size of 500 x 500

ARCHITECTURE:
Preprocessing 
Rescaling: The Pixel values are rescaled to ensure they fall within the optimal range for neural networks. 
Centering Mean Values: Pixel values are centered based on mean values. Aims to normalize the data and ensure it is centered around zero.
Channel-wise Color Normalization: Specific color normalization, possibly channel-wise, to balance color information. Aligns input data with the color expectations of the model.

CONCLUSION:
In recent years, deep learning algorithms have shown promising results in predicting the onset and progression of glaucoma, a leading cause of irreversible blindness. These algorithms have achieved accuracy and sensitivity in detecting early signs of glaucoma, with that the Xception model its high accuracy marks a significant stride towards effective medical imaging solutions.




