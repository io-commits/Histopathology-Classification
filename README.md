# Histopathology_Classification_DNN

**Introduction - Classification of histopathology images**

This project is about developing Deep Learning Model (DNN) for histopathology images classification.  
Histopathology refers to the microscopic examination of tissue in order to study the manifestations of disease. (Source - Wikipedia)  
By developing such DNN model, we can automate and improve the diagnostic process.  
Notebook Content:

The following notebook consist of 3 main parts:

   * Part 1 - Training different DNN models and evaluating their performences for the classification task.  
   * Part 2 - Plotting Confusion matrix, PCA and TNSE visualization (For best performing model from part 1).  
   * Part 3 - Coloring Large histopathology images (5000 x 5000 x 3 RGB ), for tumor and other cells representation.  

**The dataset:**

Colorectal histology dataset:  
Classification of textures in colorectal cancer histology.  
5,000 Examples. Each example is a 150 x 150 x 3 RGB image of one of 8 classes:  

   * Tumor
   * Stroma
   * Complex
   * Lympho
   * Debris
   * Mucosa
   * Adipose
   * Empty

![index](https://user-images.githubusercontent.com/7150655/123632798-05566300-d821-11eb-9331-0c478fc7d230.png)

**Results:**

Using Transfer Learning of VGG16 model with CNN, Data Augmentation, and preprocessing:  
The best model achived Accuracy score of 93.4% for cells recognition and 95.5% for Tumor recognition  

Left - Original histopathology image  
Middle - Classification of different cells  
Right - Tumor Probability  

![result](https://user-images.githubusercontent.com/7150655/123633028-549c9380-d821-11eb-8306-6f0d5b45dc39.jpg)
