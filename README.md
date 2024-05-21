# Speech Emotions Recognition

### Introduction:
<div style="text-align: justify"> Identifying emotions in spoken language is essential to building flexible and responsive human-computer interactions. Our project suggests a new model that makes use of data science innovations to overcome existing constraints by leveraging advanced techniques, larger datasets, and a shortage processing time. </div>

### Data Description:
<div style="text-align: justify"> The utilized dataset is a combination of three popular audio data sets, which are CREMA-D, RAVDESS, and SAVEE. Those datasets include seven emotion classes, which are "happy, sad, fear, neutral, disgust, anger, and surprise." and the minimum class is surprise, and we eliminate it to avoid data imbalance. The total amount of data is 9,108 audio files. </div>

### Data Pre-processing and Expirements:
<div style="text-align: justify"> We parallize pre-processing and feature extraction by using ThreadPoolExecutor and speed up the sequential extraction from 90 minutes to 20 minutes by parallel computing. and we do two different preprocessings and experiments. First, we extract only MFCCs from clips and augmented data by adding noise, shifting, and stritching. Also, the LSTM model achieves 76% accuracy. Second, we extract ZCR, RMS, and MFCCs, and data augmentation is done by shifting and adding noise. As a result, the CNN model reached 86% accuracy. </div>
