# Assignment 6 Part 2 - Writeup

---

## Question 1: Feature Importance

Based on your house price model, rank the four features from most important to least important. Explain how you determined this ranking.

**YOUR ANSWER:**
1. Most Important: 1) Bedrooms
2. 2) Bathrooms
3. 3) Age
4. Least Important: 4) Squarefeet

**Explanation:**
The reason I ranked the items like this is because they're ranked in how great their coeffients are. If it's a larger number, then it'll have a larger impact. With this in mind, with Bedrooms having the larger coefficient and Squarefeet having the smallest, this allows to rank them based on what had the major impact. Bathrooms and Age had a middle impact, and Squarefeet had last so it would be last on the list. Despite age being negative and with defintion it would be the least, we only consier the absolute value which is why it's #3.
---

## Question 2: Interpreting Coefficients

Choose TWO features from your model and explain what their coefficients mean in plain English. For example: "Each additional bedroom increases the price by $___"

**Feature 1:**
The first feature is squarefeet. For each squarefeet included, it increases the price by $121.11

**Feature 2:**
The second feature is bedrooms. For each addiitonal bedroom, the total price is increased by $6648.97

---

## Question 3: Model Performance

What was your model's R² score? What does this tell you about how well your model predicts house prices? Is there room for improvement?

**YOUR ANSWER:**
My model's R^2 score was 0.9936. This tells me that my model predicts 99.36% of the time from price variation, so it does predict really well. Despite it being really close to 100%, the fact that it isn't 100% means that there's still room for improvement. I wouldn't necessarily know what to do, but there is room for improvement.
---

## Question 4: Adding Features

If you could add TWO more features to improve your house price predictions, what would they be and why?

**Feature 1:**
Location/Neighberhood

**Why it would help:**
Some houses are more expensive/luxurious depending on where the're constructed, and it can be vice versa with it being cheaper. It overall depends on the location of the houe.

**Feature 2:**
Company building the house

**Why it would help:**
There could be some companies who charge more money when it comes to constructing houses. Some companies might focus on pure passion and construction, while some might focus purely on the profits and money so the prices could vary depending on who made the house.

---

## Question 5: Model Trust

Would you trust this model to predict the price of a house with 6 bedrooms, 4 bathrooms, 3000 sq ft, and 5 years old? Why or why not? (Hint: Think about the range of your training data)

**YOUR ANSWER:**
I would not trust the model to predict the price of this new house purely because everything is out of my data range. Despite it being really close and similar to the range, it would probably provide a sufficient answer, but it wouldn't be accurate or as reliable as the data which falls within my range.

