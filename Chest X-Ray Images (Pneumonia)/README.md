Dataset Link: https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia/discussion/183643 \
Two Approaches used: \
1. InceptionV3 with no class weights.
2. InceptionV3 with class weights for normal case as there is an imbalance in the dataset. 
The second model performs better and gives better results on hidden data as it accounts for the imbalance.
