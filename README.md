# Mobile-Price-Range-Prediction-Classification

### **Problem Statement:**
**In the competitive mobile phone market companies want
to understand sales data of mobile phones and factors which drive the prices.
The objective is to find out some relation between features of a mobile phone(eg:- RAM,
Internal Memory, etc) and its selling price. In this problem, we do not have to predict the
actual price but a price range indicating how high the price is.**
### **Data Description -**
* **Battery_power** - Total energy a battery can store in one time measured in mAh
* **Blue** - Has bluetooth or not
* ***Clock_speed*** - speed at which microprocessor executes instructions
* ***Dual_sim*** - Has dual sim support or not
* ***Fc*** - Front Camera mega pixels
* ***Four_g*** - Has 4G or not
* ***Int_memory*** - Internal Memory in Gigabytes
* ***M_dep*** - Mobile Depth in cm
* ***Mobile_wt*** - Weight of mobile phone
* ***N_cores*** - Number of cores of processor
* ***Pc*** - Primary Camera mega pixels
* ***Px_height*** - Pixel Resolution Height
* ***Px_width*** - Pixel Resolution Width
* ***Ram*** - Random Access Memory in Mega Bytes
* ***Sc_h*** - Screen Height of mobile in cm
* ***Sc_w*** - Screen Width of mobile in cm
* ***Talk_time*** - longest time that a single battery charge will last when you are
* ***Three_g*** - Has 3G or not
* ***Touch_screen*** - Has touch screen or not
* ***Wifi*** - Has wifi or not
* ***Price_range*** - This is the target variable with value of 
* 0(low cost), 
* 1(medium cost),
* 2(high cost) and
* 3(very high cost).
* Thus our target variable has 4 categories so basically it is a Multiclass classification problem.
#Conclusions:
*  In this project, we worked on a mobile price range prediction problem wherein we had to classify the price range with different classification algorithms to check the performance of the data.
*   The dataset contained about 2000 records, and 21 attributes.
*  This dataset contains no null values,duplicate values and missing values and doing exploratory data analysis (EDA).
*   price_range is our target/dependent variable and there is no imbalance in target variable.
*   Mobiles having RAM more than 3000MB falls under Very high cost category.As RAM increases price range also increases.
Mobiles having RAM less than 1000 MB falls under low cost category.
* In Decision Tree Classifier the Train accuarcy has been reduced to 97% from 100% and test accuarcy is increased by 2% . Thus we somewhat reduced the overfiiting by reducing the training accuarcy. However this will not be good model for us.
*  In Random Forest and  Gradient Boosting Classifier the Train accuracy is same but the Test accuracy is decreased slightly.
*  In XGBoost classifier the Train accuracy is decreased from 100 to 98 but the Test accuracy remains same, hence this model is slightly overfitted 
* In Support Vector Machine the Train accuracy is same but the Test accuracy is increased from 90 to 97 percent.SVM performed very well as compared to other alogorithms.
* From the above algorithms we can conclude that Support Vector Machine with using hyperparameters we got the best results.
