# Food_Image_Classifier
Food image classifier for the given 6 classes of Food images
Input: 
The FoodImage folder contains sub-folders
  ApplePie, 
  BagelSandwich, 
  Bibimbop, 
  Bread, 
  FriedRice, 
  Pork. 
Each folder contains less than 100 images of cooresponding food. 

Deep learning models typically require a large amount of diverse data to generalize well, hence  transfer learning is a recommended. 
Transfer learning involves utilizing a pre-trained model on a large-scale dataset and fine-tuning it for your specific task with a smaller dataset. 
When you set  weights='imagenet', resnet152v2_weights_tf_dim_ordering_tf_kernels_notop.h5" will be automatically downloded. 

InceptionV3 pre-trained .h5 provides a better accuracy than resnet. It has a good balance between model size and accuracy, making it a suitable choice for smaller datasets or limited computational resources. It provides a accuracy of 58.67% 

Further few shot classifier can perform well on the smaller dataset. 

Given code Food_Classifier.ipynb contains a code to train for given food images. The resulting weight file is saved as model_weights.h5 file. 
