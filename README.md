# Atrial-Fibrillation-using-ML
This project uses ML to detect if a person has Atrial Fibrillation or irregular heartbeats.

The project takes an ECG signal of heart as input which is converted to relevant features using HeartPy module such as,
###### BPM — heart rate (BPM), is calculated as the average beat-beat interval across the entire analysed signal (segment).
###### IBI — interbeat interval.
###### SDNN — standard deviation of RR intervals.
###### SDSD — standard deviation of successive differences
###### RMSSD — root mean square of successive differences.
###### PNN20 — proportion of successive differences above 20ms.
###### PNN50 — proportion of successive differences above 50ms.
###### HR_MAD — median absolute deviation of RR intervals.
###### SD1 — standard deviation perpendicular to identity line (Poincaré parameters[7]).
###### SD2 — standard deviation a long identtiy line.
###### S — area of ellipse described by SD1 and SD2.
###### SD1/SD2 — ratio.
###### BREATHING RATE — that is the frequency with which the heart beats is strongly influenced by.

The above features are used as input to predict whether the person has a Normal reading 'N' or an AF episode in his reading 'AF'

The accuracy of the model is 92% and f_score is 0.67

## Algorithms used:
----------------
###### • KNN classifier
###### • ANOVA based feature selection method
###### • L1 regularizer
