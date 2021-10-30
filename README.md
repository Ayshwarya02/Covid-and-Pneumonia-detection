# Covid-and-Pneumonia-detection
The COVID-19 pandemic has wreaked havoc in the daily life of human beings and devastated many economies worldwide, claiming millions of lives so far. Studies on COVID-19 have shown that older adults and people with a history of various medical issues, specifically prior cases of pneumonia, are at a higher risk of developing severe complications from COVID-19. As pneumonia is a common type of infection that spreads in the lungs, doctors usually perform chest X-ray to identify the infected regions of the lungs. In this study, machine learning tools such as LabelBinarizer are used to perform one-hot encoding on the labeled chest X-ray images and transform them into categorical form using Python’s to_categorical tool. Subsequently, various deep learning features such as convolutional neural network (CNN), ResNet50, AveragePooling2D, dropout, flatten, dense, and input are used to build a detection model. Adam is used as an optimizer, which can be further applied to predict pneumonia in COVID-19 patients. The model predicted Covid with an average accuracy of 93.70%. The model also efficiently reduces training loss and increases accuracy.


## Dataset :- 
https://drive.google.com/drive/folders/1e_oAxzxHZpQwMOw21LaOB9KRD1iVugaG?usp=sharing

## Model :- 
https://drive.google.com/file/d/1L5iezmq3_o1nUsmw3GJ81xgqFpNKTo0J/view?usp=sharing

## Accurancy plot :- 
![SharedScreenshot](https://user-images.githubusercontent.com/86012289/139533187-ce32206f-997c-4a4a-bace-5508f57b84b9.jpg)


## Output :- 
![WhatsApp Image 2021-10-30 at 8 32 21 PM](https://user-images.githubusercontent.com/86012289/139542288-a115f5c3-7db4-4c7e-9400-344042821b54.jpeg)


## Conclusion
This research suggests a two-stage deep residual learning technique using lung X-ray images to identify COVID-19-induced pneumonia. The model showed good performance in differentiating COVID-19 patients and patients with COVID-19-induced pneumonia using the Resent50 model. Parallel testing can be used in the current scenario to prevent infection spread to frontline workers and generate primary diagnoses to determine whether a patient is affected by COVID-19. Therefore, the proposed method can be used as an alternative diagnostic tool for detecting pneumonia cases. Future research can improve the CNN architecture performance by adjusting the hyperparameters and transfer learning combinations. Another feasible way to determine the best model for pneumonia and COVID-19 could be an improved, complex network structure.


