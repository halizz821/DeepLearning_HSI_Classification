# Vision Transformer and 2D-CNN for Hyperspectral Image Classification

![image](https://github.com/halizz821/DeepLearning_HSI_Classification/assets/135881986/b414deb7-015f-4258-8102-a2fcdc22a618)



This code classifies a hyperspectral image using a basic vision transformer and 2D CNN models.

- 2D_CNN_VisionTransformer_HSI.ipynb :
  * Before the ViT model, it employs several Conv2D layers. However, no Pooling layers were used. So, the spatial dimension of images were not changes.
 
- 2D_CNN_VisionTransformer_version 02_HSI.ipynb:
  *  Before the ViT model, it employs several Conv2D and Pooling layers. Therefore, the spatial dimension of images where changed from 21 by 21 to 3 by 3 pixels.
  *  Beacause the spatial dimesnsion was decreased significantly, we set the patch size of ViT model to 1 by 1 pixel


## Acknowledgements
This project utilizes the [EscVM_YT] ([https://github.com/EscVM/EscVM_YT]) developed by [Vittorio Mazzia] ([https://github.com/EscVM]).

The EscVM_YT played a crucial role in implementing my codes within this project.

