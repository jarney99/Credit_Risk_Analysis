# Credit_Risk_Analysis
## Overview
We were tasked with analyzing credit card risk. We used statistical analysis and machine learning to make predictions based on the data given to us. 

## Results
<img width="473" alt="Screen Shot 2022-04-21 at 2 45 11 PM" src="https://user-images.githubusercontent.com/95194554/164540706-410792fc-eea3-4217-9693-15208764126a.png">
* In the code above we are seeing the balanced accuracy score using randomoversampling. We can see that the balanced accuracy score is about 64%.

<img width="435" alt="Screen Shot 2022-04-21 at 2 47 38 PM" src="https://user-images.githubusercontent.com/95194554/164541092-4c0a0ca1-a8d5-47a7-beed-938aa3a0856f.png">
* Above we use the smote technique and see that our balanced accuracy score is about 65%.

<img width="387" alt="Screen Shot 2022-04-21 at 2 49 06 PM" src="https://user-images.githubusercontent.com/95194554/164541283-9505de3a-6bb4-42f7-8b30-2ba43b62e22f.png">
* In the code above we used the clustercentroids model to see that the balanced accuracy score is slightly lower at about 54%.

<img width="595" alt="Screen Shot 2022-04-21 at 2 51 30 PM" src="https://user-images.githubusercontent.com/95194554/164541647-f39c022f-bb2b-4a16-912f-f5eb82b3e8e4.png">
* Above we use BalancedRandomForestClassifier to get a higher balanced accuracy score of about 79%.

<img width="385" alt="Screen Shot 2022-04-21 at 2 52 37 PM" src="https://user-images.githubusercontent.com/95194554/164541819-2da56c78-6c83-47f0-843f-850aaabde104.png">
* For our last technique we use the easyensembleclassifier to get our highest balanced accuracy score of about 93%.

## Summary
After using all 6 of our machine learning models we can see that all of them would lead to over 50% accuracy, but the clustercentroids model will be the lowest at 54%. And the easyensembleclassifier will get the highest balanced accuracy score of 93%, which is why I would recommend using the easyensembleclassifier.
