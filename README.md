# Road-Sign-Detection-with-CNN

1. Download GTSB dataset from following link:

https://benchmark.ini.rub.de/gtsdb_dataset.html
Note:
  download following files
	1.FullIJCNN2013.zip
	2.gt.txt
(In our dataset folder name is maindata)

2. Save the images in yolo format required for training
(ie. jpg image and text file with same name eg.1.jpg and 1.txt)

3. Create train.txt,test.txt,data.data and classes.names file using the py files)

4. Before training download the weights required for training

link-https://pjreddie.com/media/files/darknet53.conv.74

NOTE-configuration files required for training and testing are stored in training and testing folder

5. Train the dataset using darknet
(clone the darknet repository on drive)
note:
I have used google colab for training so you need to store the files on drive)
(mount the drive)

Weights will be stored in backup folder on drive so before training create backup folder on drive

6. Test the custom detector using opencv.
Or if you have machine with darknet installed with gpu then you can test custom detector on video directly on your machine)




