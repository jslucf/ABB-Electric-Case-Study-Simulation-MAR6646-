# ABB-Electric-Case-Study-Simulation-MAR6646-
# Monte carlo simulation of multinomial logit model results for ABB Electric Case Study in MAR6646
# 2/8/17

For the ABB Electric case study, we created a multinomial logit model in Excel to estimate the probability that customers would convert their business to our firm. We were then tasked to pick the 18 customers we thought were best suited for a targeted marketing campaign. We chose these 18 based on the expected value of their revenue created by converting them into a customer.

To get a better understanding of the effectiveness of our marketing campaign, I created a monte carlo simulation of the revenue generated using those 18 customers we selected from the logit model. The data and code are attached. I also included the final output, a density curve of the results of the simulation for use in our class presentation.

Data Dictionary:

CustomerID - ID of customer in data set selected for target marketing

Size - Potential size of their account (in thousands)

District - District where customer is located

Firm.Chosen - Actual firm chosen by customer

ABB.Prob (and the other 3 "Prob" columns) - The estimated probability of customer picking a firm calculated by logit model
