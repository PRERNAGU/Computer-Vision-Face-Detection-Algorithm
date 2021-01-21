# Computer-Vision-Face-Detection-Algorithm
We will develop a computer vision algorithm to detect and identify individuals, using a database of known face images (specifically, students in the module). The dataset consists of 48 students with individual IDs and a group of students in the lecture, some of whom have not been assigned individual IDs and are ‘unknown’ to the model. The dataset consists of both individual students with ID’s, and a group of unidentified students; with their images in JPEG format and videos in mp4 format. 
************************************************************************************************************************************************************
1)We have attached a PDF report titled CV report
2) Winzip Folder Jupnotebook-video contains
i)We have attached a PDF report titled CV report
i)cnn-final-save.ipynb (Jupyter Notebook for CNN model)
ii)data-preprocessing.ipynb (Jupyter Notebook for data preprocessing)
iii)globalfeaturesfinal12.ipynb- (Jupyter Notebook for globalfeatures models)
iv)HOG12.ipynb-(Jupyter Notebook for hog models)
v)prerna-fun.ipynb(Jupyter Notebook for image recognition function) 
vi)ed12 - Jupyter Notebook - Google Chrome 2020-05-06 00-42-57 (video showing functioning of model)
************************************************************************************************************************************************************
For running Image Recognition Function on Hog features & CNN; open python notebook: prerna-fun.ipynb
The function accepts the following arguments:{ Image: ‘imagepath’; Features : ‘hog’, ‘none’; Model:  ‘SVM’,'LR', ‘CNN’, Creativemode= 0, 1}

Requirements
scikit-learn version -0.22.1.
h5py version -2.8.0.
mahotas version - 1.4.9.
keras version - 2.3.1.
joblib version -0.14.1.
numpy version -1.18.1.
pandas version -1.0.3.
opencv version -4.2.0. 3.


since the attachment size was exceeding 200MB; we have uploaded the most relevant models:
1)winzipfile: trainedmodels1updated contains
i)modelCNN1.h5 (presaved CNN model)
ii)supportVMHOGmodel.sav (presaved hog SVM model)
iii)haarcascade_frontalface_default (Harras-Cascade-Face-Extractor)

************************************************************************************************************************************************************
For running Image Recognition Function on global features; open python notebook: prerna-fun.ipynb
The function accepts the following arguments:{ Image: ‘imagepath’; Features : ‘globalfeatures’; Model:  ‘SVM’,'LR', ‘KNN’, Creativemode= 0, 1}

Requirements
scikit-learn version -0.22.1.
h5py version -2.8.0.
mahotas version - 1.4.9.
keras version - 2.3.1.
joblib version -0.14.1.
numpy version -1.18.1.
pandas version -1.0.3.
opencv version -4.2.0. 3.

2)winzipfile: globalfeaturemodelsupdated contains
i)KNNGF1model.sav-(pretrained global features KNN model)
ii)LOGGLmodel.sav-(pretrained global features Logistic Regression model)
iii)SupportvectormachinemodelGL.sav -(pretrained global features SVM model)
iv)haarcascade_frontalface_default (Harras-Cascade-Face-Extractor)

