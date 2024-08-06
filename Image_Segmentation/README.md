# In this project, Image Segmentation has been demonstrated with the use of  the Carvana dataset. The algorithm used is U-NET.

### The Carvana dataset consists of high-resolution images of vehicles with their corresponding segmentation masks. The primary task lies in differentiating vehicles from diverse and complex backgrounds. This is a challenging problem given that there is variability in vehicle appearances, the backgrounds could be starkly different with varied lighting conditions, and the image quality could be highly divergent over a range. The main goal, in the given scenario becomes to develop an effective image segmentation model in order to accurately segment and isolate the vehicle from the background. Effective vehicle segmentation is crucial for applications in inventory management, automated vehicle processing, and enhanced object recognition, etc.

# How it has been solved 

###  To address this major and challenging problem of car segmentation in the Carvana dataset, a convolutional neural network architecture, U-Net have been applied. U-net has been designed specifically for image segmentation tasks. 
### At the pre-processing stage, resizing images, normalizing pixel values, etc are performed to increase robustness of the model by improving data. 
### In the implementation of the U-Net architecture, the encoder extracts feature through down sampling layers. While by up sampling layers, the decoder reconstructs the segmentation map. Subsequently, skip connections aid in preserving spatial information as well as improving segmentation accuracy.
### In the third stage, the U-Net model is trained on the Carvana dataset. For this purpose,  a suitable loss function, in our case the binary cross-entropy loss is employed. Afterwards, an appropriate optimizer, such as Adam, is used to optimize it. In the whole process, validation techniques are implemented to monitor performance and prevent overfitting.
### In the evaluation stage, the performance of the model is assessed using metrics such as Dice score. This ensures the accuracy of the segmentation results as well as the quality.
