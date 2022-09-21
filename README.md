# Sleep Stage Classifier Models using Sklearn

The dataset used in this notebook was collected by researchers at the University of Michigan [1]. The dataset contains raw physiological signals for 31 subjects, recorded using an Apple Watch device over a 7- to 14-day ambulatory recording period. These signals include x, y, z acceleration (in units of g) and heart rate (in bpm, measured from photoplethysmography), as well as labeled sleep scored from gold-standard polysomnography (PSG) during an eight hour sleep opportunity on the final night of the recording period.

In the paper associated with the aformentioned study, the authors investigated the performance of four different algorithms at both sleep/wake and wake\/NREM\/REM classification. The best-performing algorithm for boths tasks was a Neural Network classifier, scoring 90% of epochs (or windows) correctly for binary sleep/wake classification and 72% accuracy when differentiating wake, NREM and NREM sleep. The authors suggested that classification models capable of distinguishing the more granular sleep stage labels available from PSG would be a good direction for future work.

In the Classification notebook, we experiment with various different classification models with the goal of being able to predict which of the five different stages of sleep a subject is in given their physiological signals, i.e. 0 $\Leftrightarrow$ wake; 1-4 $\Leftrightarrow$ progressively deeper stages of NREM sleep and 5 $\Leftrightarrow$ REM sleep. The notebook structure is as follows:

**1.**   Data Preparation  
**2.**   Feature Engineering  
**3.**   Regression  
**4.**   Classification  
**5.**   Validation of the Models  
**6.**   Conclusion  
