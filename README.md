# Intro to Descriptive Statistics

## Constructs: 
Multiple ways of measuring a quantity. For example, intelligence can be measured by IQ tests, grades, effort. Age can be measured in years, maturity and wisdom.

## Statistical Symbols: 
* Population Mean (µ)
* Sampling statistic/mean (x̅)
*	Sampling Error (µ - x̅)

## Surveys
Trustworthiness of a survey results depend on three factors, which are:
* Good sample size: How many individuals were surveyed?
* Representative sample: Who were surveyed?
* Sound methodology: How the survey was conducted?

### Upsides:
* Relatively inexpensive
*	Can be conducted remotely
*	Anyone with access can analyse data
*	Easy way to get info on population
### Downsides:
*	Untruthful/Fake responses
*	Biased responses (responses based on their values, beliefs & experience in life)
*	Respondents failing to understand or misinterpret the question
*	Non-response bias (respondents refusing to answer)

### Conducting a survey
*	Create a control group which will help compare the test result
*	Deception/Blinding – Respondent are not made aware of the nature of treatment given to them, which prevents bias or change in responses due to research. For example, testing the effectiveness of a drug can be conducted by assigning a random set of people an active pill and remaining people (control group) a placebo/ inactive pill or fake treatment.
* Sometimes, the researchers are not made aware of the kind of treatment given to participants which will prevent bias in favour of drug/active pill

## Measures of Central Tendency
### Mean
Commonly referred to as average is sum of observations divided by total number of observations.

### Median
Central value of data.

### Mode
Value with highest frequency

### Range
Difference between maximum and minimum value in the observations. Range is not a good representative of variability which could be influenced by the presence of extreme values.

### Quartiles		

*	Q1: Median of the first half
*	Q2: Median of all observations
*	Q3: Median of the second half
*	Q3 – Q1: Interquartile range
*	Outliers can be considered where values are less than $Q1 – 1.5 (IQR)$  OR  Values > Q3 + 1.5 (IQR)
	For two sets of observations if IQR1 > IQR 2, then the box plot spread is high. 
	Mean will not always be in between IQR except of symmetrical distribution.
	IQR does not tell us anything about the distribution (especially the shape) except for the range of values. 

## Measuring Variability
### Option 1: Avg. distance between two data values
For three data points there will be 6 distances to calculate and with each addition of point the number of distances to be calculated will increase exponentially.

### Option 2: Avg. distance between each data value and either the min or max
A single outlier would disrupt the variability and wouldn’t give us any indication about the distance.

### Option 3: Mean of deviations
Mean is a good reference point. It will take every point in account and will exist in the middle.

* Mean Deviation =  ∑(x_i- x̅)/N
The mean deviation will always amount to Zero. Hence to measure variability we square the sum of deviation and take their mean
* Variance (σ^2)=  ∑(xi-x̅)^2/N
* Standard Deviation (σ)= √(∑(x_i-x̅)^2/N) = √(σ^2 )

## Standard Deviation
For a normal distribution
* 68% of the value s lie between 
*	95% of the values lie between (x̅ – 2σ) & (x̅ + 2σ)

### Bessel’s Correction
Since the sample is usually from (x̅ – σ) & (x̅ + σ) or (x̅ – 2σ) & (x̅ + 2σ), the variability of sample is smaller than population variance.
* σ_sample < σ_population
* To account for this variation reduction, we introduce Bessel’s correction.
* Sample Variance (s^2)=  ∑(x_i-x̅)^2/(n-1)
* Sample Standard Deviation (s)= √(∑(x_i-x̅)^2/(n-1)) = √(σ^2 )
* Bessel’s correction is applied to estimate the population standard deviation.

