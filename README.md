# Confusion Matrix
TP=True Positive: Predicts hospital provides quality care and is true
FP=False Positive: Predicts hospital provides quality care but is not true
FN=False Negative: Predicts hospital does not provide quality care but not true
TN=True Negative: Predicts hospital does not provide quality of care and is true

## Busniness Value

Business value would be identifying whether the hospital institution provides quality of care.  This would allow to develop or pivot organizational strategy to sustain or enhance quality of care therefore increasing patient visits for revenue and directly improving hospital rankings (US News and World Report Hospital Rankings, Leap Frog Grades, CMS stars) and reputation.  

Business Value Metrics: 
•	Hospital Ranking improvement.
•	Hospital patient revenue
•	Patient experience improvement

### Confusion Matrix Example Using Dummy training Data 

True Quality	Y	N	N	Y	N	Y
Predicted Quality	Y	N	Y	N	N	N

Accuracy =[(TP+TN)/(TP+FN+FP+TN)] =50%
Precision=[TP/(TP+FP)] = 50%
Recall=[TP/(TP+FN)] = 33%

Assignment1 CS 5260

[comment]: <> (Predicted quality is fine, but rewording True Quality to Quality Care Provided would help readers without a STEM background understand that this is sample data being compared to your model's prediction.)
[comment]: <> (Might be a good touch to add in how much value you estimate good care would add to a hospital's bottom line. I'm assuming the dataset has hospitals in locations that have wide gaps in surrounding population. Total value added would vary widely, but mentioning the value added per patient might give the reader more insight into what improving their ranking will do financially.)
