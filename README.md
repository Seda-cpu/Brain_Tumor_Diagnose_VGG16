# Brain_Tumor_Diagnose_VGG16
Transfer learning and classification of brain tumor dignose from MRI images. 

I use Brain MRI Images for Brain Tumor Detection dataset for this project. Here is kaggle link 
https://www.kaggle.com/navoneel/brain-mri-images-for-brain-tumor-detection


The dataset consist of yes and no class of brain tumors.
![indir](https://user-images.githubusercontent.com/74606830/143949866-0a300c1f-2266-40e9-aa9a-bff4ae074f94.png)


For making the dataset better I find the biggest contour and crop the images with using OpenCV. 

![indir (1)](https://user-images.githubusercontent.com/74606830/143950027-cffdd863-5650-4080-8ad2-f092e23decdd.png)

Then I use this images with VGG16 pretrained weights. You can see the results of VGG16 from notebook. 
