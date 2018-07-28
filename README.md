# ImageClassifierForHelmet
The primary goal of this project is to implement image classifier using tensorflow to classify images on the presence of helmet in them for road safety.

The project has been successfully implemented and tested with an accuracy of 86.5%. Our results do sustain our hypothesis.

This project can be very beneficial for traffic police in real world scenario and in future its accuracy can be increased with more vivid data sets and algorithms.

The dataset is collected by me using google images batch downloader. 
Here is the link https://drive.google.com/file/d/1GmNawDFGA0rguJPRbYniCge4oUjJ01Gs/view?usp=drivesdk

I have provided the label_image.py file which is used to test the model for new images.

Below is my docker id where trained model is stored.
docker attach 23eb220ba377

You just have to run the following command to test the model
python /tf_files/label_image.py /tf_files/Test_Image.jpg
