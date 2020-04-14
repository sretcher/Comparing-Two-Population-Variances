### Comparing Two Population Variances: Independent Sampling
In Archives of Pediatrics and Adolescent Medicine (Dec. 2007), a study of honey as a children’s cough remedy was conducted in which 68 children were randomly assigned to receive either a cold medicine (DM group, n=33) or honey (H group, n=35). Cough improvement scores were recorded for the two groups. Researchers wanted to know if the variability in coughing improvement scores differed between the two groups.

### Conditions Required for Valid Inferences about (σ^2(1) / σ^2(2)) 
1. The samples are random and independent.
2. Both populations are normally distributed.

From the informations given, our samples are independent since the children were randomly assigned to the two different groups. We will assume that the 68 children were randomly selected for this project.

Checking the normal quantile plots, we will assume the populations are about normally distributed. If we have doubts about the normality of the populations, we could always opt for a nonparametric method like Levene's Test. 

![histogram](NormalPlots.png)

### Hypotheses for Equal Population Variances (σ^2(1) = σ^2(2)): F-Statistic

The common statistical procedure for comparing population variances (σ^2(1)) and (σ^2(2)) makes an inference about the ratio σ^2(1) / σ^2(2). To make this inference, we will use the ratio of the sample variances s^2(1) / s^2(2) as our test statistic.  
 
When the above assumptions are satisfied and the null hypothesis is true, our F test statistic's sampling distribution is the F-distribution with n1 - 1 numerator degree of freedom and n2 - 1 denominator degrees of freedom. The F-distribution is right skewed because the ratio of sample variances can not be less than zero. 

Let σ^2(1) = population variance of improvement scores for the DM group and σ^2(2) = population variance of improvement scores for the honey group.

Ho: σ^2(1) / σ^2(2) = 1
Ha: σ^2(1) / σ^2(2) != 1

The F-distribution critical values correspond to the upper tail areas of the distribution. Because we have a two-tailed F-test, we need to make sure that  
