# Inferential-_staistics_practical

# Z-TEST / Z_SCORE

# T-TEST

# CHI-SQAURE TEST

# STEPS TO HYPOTHESIS TEST:
H0 - null hypothesis

H1 - alternative hypothesis

CI - to find critical value

ALPHA- significant value

Z_TEST,T_TEST,CHISQAURE

P_VALUE

Z_test=(sample mean-popualtion mean)/population std deviation/root n

given:

n>=30 sample size
population mean
population std deviation

IF z_score > z_critical - we reject the null hypothesis

else

IF z_score < z_critical - we fail to reject the null hypothesis

p>=0.05 we reject the null hypothesis

p<=0.05 we fail to reject the null hypothesis



# T-test

# 1. one sample t_test(with respect to one independent sample)
# 2.two sample t_test(with respect to two independent sample)
# 3.t_test (two sample from the smae population on a different time interval )

1.when we have limites sample size n<=30

2.we dont know population std deviation

one sample t_test:

hypothesis:

sample_mean=pop-mean/true mean

one_sample_t_test=(sample mean-popualtion mean)/population std deviation/root n

# practical example
# weights of 25 obese people were taken before enrolling them into the nutrition camp. 
# The population mean weight is found to be 45 kg before starting the camp. After finishing the camp, 
# for the same 25 people, the sample mean was found to be 75 with a standard deviation of 25. Did the fitness camp work?

n=25,mu=45, sample mean=75, sampel std deviation=25

we dont have population std deviation so we are going use t test

H0--> mu=45(sample mean is population or true mean)

H1--> mu!=45 ( 2 tail test)( sample mean is not population mean)


# chi-sqaure test - categorical data
 1. we are going with observed data - expected data
