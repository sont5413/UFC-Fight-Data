## Predicting Winners of UFC Fights
I built two classification models to predict the winner of a UFC fight based on age, height, and so on of the "red" fighter and the "blue fighter.
* Random Forest 
* Gradient Boosting

The Random Forest  model had the least mean absolute error and differed from the observed winner about 40% of the time.  In other words, it predicted the correct winner about 60% of the time!


#### Figure. Clearly no feature alone has huge explanatory power. In fact, most have very little explanatory power (roughly ≤ 0.03). However, the number of UFC fights a fighter had previously "BPrev" had the most predictor power.

![image](https://user-images.githubusercontent.com/95881308/177015092-8a2329ed-2c68-43e5-9e70-3e13c80a5441.png)
