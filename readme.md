This project was a simple trial when I first started learning Yolo. The content classification of the game screen only includes heroes, soldiers and  towers. There are only about 300 labels with yolov5s model. However, thanks to the powerful performance of Yolo, the recognition effect is still unexpected.

'results show.mp4' shows the classification of scenes with more content. It can be seen that there are still many errors, mainly due to incomplete label types and less training samples.

'my_data' folder in the compressed package contains my training set and the weight file obtained from training, 'trans.py' file is a program that converts .json files obtained through 'labelme'  into .txt files. You can make more labels to enhance the recognition effect.

Let's go together.
