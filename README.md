# MusicGo

An Android application that uses Brain signal data to detect the stress levels of a person and play appropriate music according to the mood of the user. The Brain signal data (EEG) is validated with the Galvanic Skin Response (GSR) and ECG data, which serve as ground truths for the brain signal data.

Machine Learning is an interesting part of Artificial Intelligence that exists all around us. In this data driven world where data powers almost all technologies, Machine Learning is among the first concepts to take advantage of the myriad of data present all around us. As the data is fed into the Machine Learning system, it ‘learns’ patterns amongst the data and predicts correct results when new data is fed into it. In this project we have made use of the various Machine Learning algorithms to be applied on Brain signal data to suggest music to the user according to the mood detected by the ML algorithms

The architecture consists of 3 systems. The configurations and functions are described below:
1. Android device
Make and Model: Motorola G7 Play
OS: Android 9.0 (Pie)
2. Fog Server (Local Server) coupled with NGROK [5]
Setup on the same network as the Android phone. Make and Model: Acer Predator Helios 300
OS: Windows 10 Home 64-bit
Processor: Intel i7 7th generation RAM: 16GB DDR5
3. Machine Learning Models: Decision tree, KNN, Random Forest and XGBoost built on the training data from EEG with ECG and GSR data as ground truth.
OS: MAC
Processor: Intel i5 8th generation RAM: 16GB DDR5

The android device communicates with the server that executes the machine learning prediction using the saved models. The server then sends back the result to the android device that then plays the music according to the response received from the server. 

# Link for the App
https://drive.google.com/open?id=1GcuzjFbAqFkCPKgLSBNNNjAsve4CBPDa
