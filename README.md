# Linear-Models
Restoring cadmium(Cd) contaminated soil with grass

It was of interest to study the detoxifying capacity of Eremochloa ophiuroides in Cd contaminated soils. 

Experimental Design:

   20 pots of soil with this grass were assigned 5 different dosis of Cd (60, 120, 180, 240 and 300 mg Cd per kg)

   Each dose of Cd was assigned 4 pots.

   36 days in the grenhouse accumalated Cd was measured in the plant as: Cd per kg of dried plant weight.

  
Model Description:

   A linear relationship is suspected. The Response Variable (RV) is accumalated Cd. The Explanatory Variable (EV)
   which is Cd dosage is the deterministic part of the analysis. All statistic models have an error (E) asociated with them
   and is called the stocastic part of the analysis and it contemplates the: 1) inherent aleatory process 2) The effect of
   other EV not included in the model and 3) measuring error. This error is assigned a probability distribution and in this case
   it is assigned a normal distribution since the RV is a continuos variable. 
   **Y**i = **B**0 + **B**1**X**i + **E**i

Yi is the i-eth observation of the dependent variable Y
Xi is the i-eth value of the predictor variable X
B0 and B1 are the parameters Intercept and Slope (regression coefficients)
Ei is the aleatory error, the variation of Y not explained by X ( E ~ NID (normal distribution) (0, sigma^2) (with a mean value of 0 and variance = sigma^2)
