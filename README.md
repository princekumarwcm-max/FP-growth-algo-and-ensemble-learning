# FP-growth-algo-and-ensemble-learning
✅ 1. FP-Growth Algorithm (Frequent Pattern Growth)  FP-Growth is an algorithm used in data mining to find frequent itemsets without generating candidate sets.
⭐ Simple Explanation:
(1)FP-Growth finds patterns like:
(2)Which items are frequently bought together?
(3)What combinations appear often in a dataset?

#Example:
If many customers buy Milk + Bread, it detects that pattern.

✔️ How FP-Growth Works:
Step 1: Build an FP-Tree (Frequent Pattern Tree)
(1): Scan data to find item frequencies
(2):Remove items below minimum support
(3):Insert transactions into a tree structure
(4):Items with same prefixes share paths → makes it memory efficient

Step 2: Extract Frequent Patterns
(1)Traverse the FP-Tree from bottom to top
(2)For each item, create a conditional tree
(3)Recursively find patterns that meet minimum support

✅ 2. Ensemble Learning
Ensemble Learning means combining multiple machine learning models to create a stronger, more accurate model.

⭐ Simple Explanation:
“Many weak models working together to become a strong model.”
Exactly like:
One person can be wrong
But 10 people together give a better decision

Types of Ensemble Learning
1️⃣ Bagging
(1)Multiple models of the same algorithm
(2)Trained on different random samples
(3)Final result: majority vote / average

Example:
Random Forest (most popular bagging algorithm)
2️⃣ Boosting
(1)Models are trained sequentially
(2)Each new model fixes previous model's mistakes
(3)Ends with a very strong model

Examples:
AdaBoost
Gradient Boosting
XGBoost
LightGBM
CatBoost

3️⃣ Stacking
(1)Combine predictions of different models (SVM, Logistic, DT, RF)
(2)A meta-model makes final prediction
