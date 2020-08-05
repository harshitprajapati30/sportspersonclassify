This project is just an introduction to OpenComputerVision.
In this I have used the haarcascades and detected two eyes in the cropped image. It involves manual cleaning of the dataset too. The model uses classification techniques with hyperparameter tuning. It is not much effective as the image is converted to gray form and region near the eyes is used for classification.
Wavelet transform is helpful in extraction of the features of an image.
Training is done on the cropped images. Vertical stacking of the gray and original image has been used for training purposes.
Only 5 sports persons are taken for model building. For images other than this will fail to classify and following message is poped out "Can't classify image. Classifier was not able to detect face and two eyes properly".
This can be further deployed on platforms in the similar manner as Banglore Home Price Prediction Project.