Face Predictor with Transfer Learning

Transfer Learning: As the name suggests is storing knowledge gained while solving one problem and applying it to a different but related problem.

Here's a quick overview of making this Face Predictor:

Step 1:Loading the weights from the Pre trained Model. 
Here I have used MobileNet architecture and downloaded the pretrained weighs that were trained on ImageNet dataset.

Step 2: To apply this gained knowledge, I collected dataset using OpenCV and divided it into 2 separate folders for Training and Testing (Validation).

Step 3: To increase the dataset and to make the model learn better, I have used the concept of Augmentation (Transforming images)

Step 4: Now comes the part of Adding the layers in this architecture. Added a Fully Connected Layer at the end of the existing model before the Output Layer.

Step 5: Compiled the entire model. Attaching those new layers to the existing model. Trained the model with Training Data splitted before. Saved the model too.

Step 6: Tested the model with the Validation dataset. 

And done with the Face Prediction using the concept of Transfer Learning.
