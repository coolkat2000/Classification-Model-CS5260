# Confusion Matrix

![image](https://github.com/coolkat2000/Classification-Model-CS5260/assets/143561378/9ac1f31b-2b8e-4b1c-b468-b987614bee2e)


TP=True Positive: Predicts hospital provides quality care and is true
FP=False Positive: Predicts hospital provides quality care but is not true
FN=False Negative: Predicts hospital does not provide quality care but not true
TN=True Negative: Predicts hospital does not provide quality of care and is true

## Busniness Value

This model would allow various stakeholders to determine whether the hospital institution(s) provides or will provide quality of care.  This would allow to develop or pivot organizational strategy to sustain or enhance quality of care therefore possibly increasing patient visits for revenue and directly improving hospital rankings (US News and World Report Hospital Rankings, Leap Frog Grades, CMS stars) and reputation.  

Business Value Metrics: Potential Improvements
•	Hospital Ranking improvement.
•	Increasing hospital patient revenue
•	Patient experience improvement


### Confusion Matrix Example Using Dummy training Data 

![image](https://github.com/coolkat2000/Classification-Model-CS5260/assets/143561378/83937a38-a5e5-46dc-86c2-f0b3a2a0f324)

![image](https://github.com/coolkat2000/Classification-Model-CS5260/assets/143561378/0bdd5d23-0983-41aa-a85f-98fa35b995bd)


Accuracy =[(TP+TN)/(TP+FN+FP+TN)] =50%
Precision=[TP/(TP+FP)] = 50%
Recall=[TP/(TP+FN)] = 33%

Assignment1 CS 5260

[comment]: <> (Predicted quality is fine, but rewording True Quality to Quality Care Provided would help readers without a STEM background understand that this is sample data being compared to your model's prediction.)
[comment]: <> (Might be a good touch to add in how much value you estimate good care would add to a hospital's bottom line. I'm assuming the dataset has hospitals in locations that have wide gaps in surrounding population. Total value added would vary widely, but mentioning the value added per patient might give the reader more insight into what improving their ranking will do financially.)
