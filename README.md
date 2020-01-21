# Statistical-Inference-Gender-BMI
 Analyzing the distribution of BMI , Performing hypothesis testing to check if the mean of BMI for Female differ from BMI of Male.
 
 
 #### Objective & Approach : Statistical Inference of BMI 
 * Estimating the population distribution of BMI using Empirical CDF
 * To find the point estimate of median of BMI and 95 % confidence Interval ( Normal CI, Pivotal CI, Quantile CI) for it using Parametric and Non Parametric Boostrap
 * Finding the Maximum Likelihood Estimation of the mean of BMI for the two genders 
 * To see if there is a difference between the mean of BMI for two genders using Hypothesis Testing
 
 
 #### Results:
 * 80 percent of the people in this dataset are overweight or obese(Based on ECDF)
 * The estimated standard error of sampling distribution of median from bootstrap is 0.896
          *The point estimation for the median of the BMI is 36.597
          *The normal confidence interval is [35.165,38.749]
          *The pivotal confidence interval is [35.396,39.076]
          *The quantile confidence interval is [34.8,38.518]
 * Difference of Mean BMI of two genders:
          *The Maximum likelihood estimate is given by the value 0.7575097
          *The estimated standard error was found using parametric bootstrap
          *Then using the MLE and standard error, a confidence interval was built – (-1.751231,3.141853)
 * We cannot make any conclusions about the difference of mean of male BMI and female BMI based on the hypothesis test performed
