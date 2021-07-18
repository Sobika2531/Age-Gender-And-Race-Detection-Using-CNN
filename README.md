# Age, Gender and race detection using Convolutional Neural Network
Automatic age and gender classification has become relevant to an increasing amount of applications, particularly since the rise of social platforms and social media. Nevertheless, performance of existing methods on real-world images is still 
significantly lacking, especially when compared to the tremendous leaps in performance recently reported for the related task of face recognition. In this project I showed that by learning representations through the use of deep convolutional neural networks (CNN), a significant increase in performance can be 
obtained on these tasks. To this end, I used a simple convolutional net architecture that can be used even when the amount of learning data is limited. I evaluated my model on the recent UTKFace dataset for age, race and gender estimation and show how it dramatically outperforms current state-of-the-art methods.

## Dataset used
I have used a dataset called UTKFace. UTKFace dataset is a large-scale face dataset with long age span (range from 0 to 116 years old). The dataset consists of over 20,000 face images with annotations of age, gender, and ethnicity. This dataset serves as a benchmark for face photos and is inclusive of various real-world imaging 
conditions like noise, lighting, pose, and appearance.

The labels of each face image is embedded in the file name, formated like [age][gender][race]_[date&time].jpg

--> [age] is an integer from 0 to 116, indicating the age

--> [gender] is either 0 (male) or 1 (female)

--> [race] is an integer from 0 to 4, denoting White, Black, Asian, Indian, and Others (like Hispanic, Latino, Middle Eastern).

--> [date&time] is in the format of yyyymmddHHMMSSFFF, showing the date and time an image was collected to UTKFace.

Sample input images have been uploaded for quick reference.

##  
This project was made as a mini-project for the course CS6301 - Machine Learning

For docs and info contact sobikasenthilnathan@gmail.com
