# # Suspicious Activity Detection Using Neural Networks
![suspicious thumbnail](https://raw.githubusercontent.com/ranabhatshree/Suspicious-Activity-Detection-Using-NN-New-/main/suspecious_activity.jpg)

An Intelligent surveillance system that can monitor the human activities from videos and categorize them as usual and unusual activities.
System will identify the type of activities (Fighting, Explosion, Burglary, Normal, etc.) If it is suspicious then it predicts with the respective classes.

## Objectives
- To compare suspicious activities in the different neural network architecture.
- To predict the suspicious class e.g: Fighting, Normal etc. from the videos. 

## Datasets 
CRCV | Center for Research in Computer Vision at the University of Central Florida (ucf.edu) [Link](https://www.crcv.ucf.edu/projects/real-world/)

![Data.png](https://raw.githubusercontent.com/ranabhatshree/Suspicious-Activity-Detection-Using-NN-New-/main/data.png)

## Methodology
1. Single & Average Frame CNN:
![Single Frame CNN](https://raw.githubusercontent.com/ranabhatshree/Suspicious-Activity-Detection-Using-NN-New-/main/1.%20Single%20Frame%20CNN/V2-Azure_with_more_data/Single%20Frame%20CNN.png)
[Code: Jupyter Notebook](https://bit.ly/36BbDpJ)
#### Result:
![Accuracy](https://raw.githubusercontent.com/ranabhatshree/Suspicious-Activity-Detection-Using-NN-New-/main/1.%20Single%20Frame%20CNN/V2-Azure_with_more_data/accuracy.png) 

![Loss](https://raw.githubusercontent.com/ranabhatshree/Suspicious-Activity-Detection-Using-NN-New-/main/1.%20Single%20Frame%20CNN/V2-Azure_with_more_data/loss.png)

![Confusion Matrix](https://raw.githubusercontent.com/ranabhatshree/Suspicious-Activity-Detection-Using-NN-New-/main/1.%20Single%20Frame%20CNN/V2-Azure_with_more_data/confusion%20matrix.png)


2. Inceptionv3 + GRU:
![Model2](https://raw.githubusercontent.com/ranabhatshree/Suspicious-Activity-Detection-Using-NN-New-/main/3.%20Inception%20GRU/Blank%20diagram.png)

3. ConvLSTM:
![Model 3](https://raw.githubusercontent.com/ranabhatshree/Suspicious-Activity-Detection-Using-NN-New-/main/4.%20CONVLSTM/Blank%20diagram.png)
