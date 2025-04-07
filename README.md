
# Comparative Study On Music Genre Classification Using Machine Learning Models

In this dissertation work, I have implemented two different machine learning model namely; Support Vector Machine and k-Nearest Neighbour. In this particular file, i will try to split the steps in order to provide pathway to run each particular python notebook(pynb) file

## Steps to run feature extraction
* Open the notebook `feature_extraction.ipynb` in Google Colab.
* Upload or mount the Dataset: In the Colab notebook, upload the dataset directory from this link https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification/code or mount the dataset by using these two command lines:
1)from google.colab import drive
2)drive.mount('https://drive.google.com/drive/folders/1e2Q9rnlaqI7Wpyy01Ek_r-VVgZMRFRyC?usp=sharing')

* Run the notebook cells to extract features and generate `gtzan.csv`, which i have already provided as an attachment. This gtzan file consists of 6 distinct features which i have had extracted for


## Steps to run Support Vector Machine Model
* Open the notebook `SVM_Model.ipynb` in Google Colab.
* Prerequisites : Before running the feature extraction code, ensure that you have the following dependencies installed in your Google Colab environment: Librosa, NumPy, Pandas.
* Again mount or upload the dataset and now place the gtzan.csv file in the same directory.
* Run each of the cells to calculate different performance metrics.

## Steps to run k Nearest Neighbour
* Open the notebook `kNN_Model.ipynb` in Google Colab.
* Prerequisites : Before running the feature extraction code, ensure to have installed the following dependencies in your Google Colab environment: Librosa, NumPy, Pandas.
* Again mount or upload the dataset and now place the gtzan.csv file in the same directory.
* Run each of the cells to calculate different performance metrics.









## Screenshots

These are the respective outputs i got for my both models. I have attached the screenshot of the output for better understanding. 
### SVM Code Output

![SVM Output](https://raw.githubusercontent.com/gitesh21/images/aee84514f45956a7ad67f95e70337918ee425776/01A6F6AF-252A-44BB-AF4F-EA2E8A2F7717_1_201_a.jpeg?token=ANCGNUNCBYMQXAYCRP27PX3E4YLV4)

Svm model accuracy on test data : 74.5%

### kNN Code Output

![kNN Output](https://raw.githubusercontent.com/gitesh21/images/main/F10DD597-D45E-4398-A493-F122B8668A73_1_201_a.jpeg?token=GHSAT0AAAAAACGUMP5JS77XJUXECHUS5R64ZHGDI3Q)

kNN model accuracy on test data : 67%

### Dissertation Grade : 
![Dissertation Grade](https://raw.githubusercontent.com/gitesh21/Music-Genre-Classification-using-ML-models/refs/heads/main/Dissertation%20grade.png)
