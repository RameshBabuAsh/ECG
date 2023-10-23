#ECG signal analysis

Interpreting the nonstationary, nonlinear, and complex ECG signals visually is a challenging task. Moreover, extracting task-relevant features from ECG signals can be tedious and demanding. Traditional linear methods may not be sufficient to capture the intricate dynamic variations present in ECG data. Consequently, the use of deep learning (DL)-based approaches has gained prominence in the extraction of features from ECG signals for the purpose of computer-aided diagnosis (CAD) of cardiovascular conditions. DL methods have the capability to automatically extract highly complex and nonlinear features from raw ECG data with minimal human intervention, significantly enhancing the accuracy and efficiency of cardiovascular disease diagnosis.

LINK FOR DATASET : https://drive.google.com/file/d/16aljV1fKcrhbQUyb0A3-hjdoT8d4mo_z/view?usp=share_link and https://drive.google.com/file/d/1LIL7_rF6I-Td3suYYhh-n40Ymkz_5kFd/view?usp=share_link

CONTENT:
1.	Number of Samples: 109446
2.	Number of Categories: 5
3.	Sampling Frequency: 125Hz
4.	Data Source: Physionet's MIT-BIH Arrhythmia Dataset
5.	Classes: ['N': 0, 'S': 1, 'V': 2, 'F': 3, 'Q': 4]

NOTE: Each row of the dataset represent R-R peak portion of the ECG graph


Accuracy: The overall accuracy of the model is 0.98, indicating that it correctly predicts the class for 98% of the instances in your dataset.
