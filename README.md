# Module-14-Challenge

### **Baseline Model:**

![image](https://github.com/Mccalabrese/Module-14-Challenge/assets/138624063/c4fd9284-039a-452f-8c4f-d1d5851bc89e)

In my baseline model, the model preformed better than the actual price movement. The actual price movement returned about 40% over the time period, while the trading algorithm returned approximatly 50%.


### **Adjusted training dataset size:**

**One Month-**

![image](https://github.com/Mccalabrese/Module-14-Challenge/assets/138624063/14d113e7-62bd-4b91-914f-a1bd9b4aafd9)

**Six Months-**

![image](https://github.com/Mccalabrese/Module-14-Challenge/assets/138624063/de3aaaf2-4a9f-4aa9-89e7-f0a41396b39e)

The impact of changing the size of the training dataset was that the decrease to one-month slightly reduced preformance, lowering the return to about 40%, whereas increasing it to six months increased the preformance significantly, with the algorithm returning about 80% over the time period.

### **Adjusting SMA:**

![image](https://github.com/Mccalabrese/Module-14-Challenge/assets/138624063/f523eb6d-9a29-4684-9017-47d10202fe8c)

I increased both SMA time frames, with my short window being increased to a 30 day SMA, and my long window increased to a 200 day SMA. This increased my algo's return to about 60%

### **Best Return:**

![image](https://github.com/Mccalabrese/Module-14-Challenge/assets/138624063/2acf0749-1fd3-4aee-8f54-a91cc6c772d1)

Based on the data above, for best returns I used the increased SMA time frames and a six month training dataset size. This cumulated in a 100% return over the time period.

### **Logistic Regression:**

![image](https://github.com/Mccalabrese/Module-14-Challenge/assets/138624063/6c421359-696d-4c69-94f6-99c5a5257b03)

The logistic regression returned worse than anything else, returning about 15% over the time period.

## **Summary Evaluation:**

The Logistic Regression model preformed worse in every iteration than baseline with the exception of the 6-month iteration, however even in this it underpreformed the tuned non-logistic regression model.

**Logistic Regression with Increased SMA Windows and Increased Training Dataset:**

![image](https://github.com/Mccalabrese/Module-14-Challenge/assets/138624063/19e88270-5628-44ff-a524-bfff8db06151)

**Logistic Regression with Decreased Training Dataset:**

![image](https://github.com/Mccalabrese/Module-14-Challenge/assets/138624063/8213ccc6-a92e-4876-ad5a-81a9d9d0c067)

**Logistic Regression with Increased SMA Windows:**

![image](https://github.com/Mccalabrese/Module-14-Challenge/assets/138624063/2d8f96d3-2cb2-4693-91d2-b28a98151bc9)

**Logistic Regression with Increased Training Dataset:**

![image](https://github.com/Mccalabrese/Module-14-Challenge/assets/138624063/05e859ba-1ac8-4534-82c0-f39876810894)


*I would recomend the tuned model for paper trading and further development. Increasing the training dataset size increased preformance, and so did increasing the SMA windows.*

![image](https://github.com/Mccalabrese/Module-14-Challenge/assets/138624063/196436d4-0592-40ed-8f4e-a1e5243de254)
