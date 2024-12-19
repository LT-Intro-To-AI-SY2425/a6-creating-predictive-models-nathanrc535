# Part 4 - Classification Writeup

After completing `a6_part4.py` answer the following questions

## Questions to answer

1. Comment out the StandardScaler and re-run your test. How accurate is the model? Why is that?
The model is not accurate at all without the standardscaler. Whle it technically did get an accuracy of 0.67, the model will always predic the gender as male even when the actual gender is female.
2. How accurate is the model with the StandardScaler? Is this model accurate enough for the given use case? Explain.
The model is farely accurate with the StandardScaler at an accuracy of 0.84. There are some wrong predictions that arise, but I think that the model is accurate enough for the given use case.
3. Looking at the predicted and actual results, how did the model do? Was there a pattern to the inputs that the model was incorrect about?
There was no pattern that I could see between the predicted and acutal results that were right and wrong.
4. Would a 34 year old Female who makes 56000 a year buy an SUV according to the model? Remember to scale the data before running it through the model.
A 34 y.o female would not buy the SUV according to this model.
