## Predicting Winners of UFC Fights
I built 3 models to predict the winner of a UFC fight based on age, height, and so on of the "red" fighter and the "blue fighter.
* Random Forest 
* Linear Regression
* Gradient Boosting
### The Random Forest Classifier model had the least mean absolute error and differed from the observed winner about 40% of the time.  In other words, it predicted the correct winner about 60% of the time!

### As shown by the figure below, clearly no feature alone has huge explanatory power. In fact, most have very little explanatory power (roughly ≤ 0.03). However, the number of UFC fights a fighter had previously "BPrev" had the most predictor power.
![image](https://user-images.githubusercontent.com/95881308/172012522-218d8f87-146d-469a-b100-7e3e42fb171f.png)
