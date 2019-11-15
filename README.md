# Lung-Detection-in-Complete-CT-Scan-Images
Detecting Lungs in complete CT Scan Images

Dataset: LUNA Dataset (https://luna16.grand-challenge.org/data/)

This is how the initial dataset looked for a slice in the complete CT scan:

![training1](https://github.com/shreyshah97/Lung-Detection-in-Complete-CT-Scan-Images/blob/master/Images/lung0.png)
![training2](https://github.com/shreyshah97/Lung-Detection-in-Complete-CT-Scan-Images/blob/master/Images/lung1.png)

Results after Training, The leftmost image is the image to be segmented, centre is the ground truth and rightmost image is the predicted result:

![result1](https://github.com/shreyshah97/Lung-Detection-in-Complete-CT-Scan-Images/blob/master/Images/lung2.png

AUC:0.9972679259671106 was achieved when tested on subset9 after training the model on subset0 to subset6.

Note - I have trained the model subset by subset as I had low mermory and no GPU. So it should run fine on any PC.
