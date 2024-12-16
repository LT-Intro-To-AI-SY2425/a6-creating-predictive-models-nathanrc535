# Part 3 - Multivariable Linear Regression Writeup

After completing `a6_part3.py` answer the following questions

## Questions to answer

1. What is the R Squared coefficient for your model? What does that mean about the model in relation to your data?
R squared value is 0.85. This is the best model so far since it is close to 1 showing a positive correlation.
2. Is your model accurate? Why or why not?
This model is the most accurate and would say is accurate enough due to the r squared value.
3. What does the model predict a 10-year-old car with 89000 miles is worth? What about a car that is 20 years old with 150000 miles?
My model predicted that the 10 y.o car is worth $9274.67. My model predicted that the 20 y.o car is worth $2299.53
4. You may notice that some of your predicted results are negative. This is occurring when the value of age and the mileage of the car are very high. Why do you think this is happening?
Since there was no boundary coded for 0, the model will continue to decrease in value as age and mileage increase. Once the value passes 0, the car will eventually be worth nothing.