# Report for Group Assignment 1.2

*[CEGM1000 MUDE](http://mude.citg.tudelft.nl/): Week 1.2, Friday, Sep 13, 2024.*

_This assignment does not need to be turned in._

_Most of the questions require you to finish `Analysis.ipynb` first, but depending on how you allocate tasks between group members, it is possible to work on this in parallel. Make sure you save time for peer reviewing each others work before completing the assignment!_

_We don't expect long answers; be as concise as possible (just a few sentences max, usually); however, it is critical to support your arguments with qualitative observations (e.g., describe specific figures) and quantitative evidence (report results of calculations, values, etc) from `Analysis.ipynb` whenever possible._

## Contents

**Question 1**

_What is the expected value and standard deviation of the ice thickness after 3 days ($\mu_H$ and $\sigma_H$)? There should be two sets of results._

Set 1: 
mu_h = 0.282
sigma_h = 0.034
Set 2: 
mu_h = 0.277
sigma_h = 0.034

**Question 2**

_Explain whether we should use the expected value for our prediction, or whether we should also account for the variability of the thickness estimate in the subsequent phases of our analysis?_

We need to take into consideration the thickness of th ice since the estimation is not 100% correct. And we need to take into account the variability of the thickness for a correct estimation.

**Question 3**

_How do we obtain the "true" distribution of $H_{ice}$, and what does it look like?_

The true distribution of H_ice stands as: the bigger the sample size, the more accurate the model becomes. It looks like a normal distribution. 

**Question 4**

_Are the propagated and simulated $\mu_H$ and $\sigma_H$ equivalent?_

They are similar. 

**Question 5**

_Is the Normal distribution a reasonable model for $H_{ice}$?_

Yes it is, but on the other hand, the prediction on the tails does not fir the normal fit, presenting with a slight change between the prediction and the generated samples. 

**Question 6**

_Using the loop in Task 3.1, explore the effect of sample size on the results. Describe the observations you make and explain why they are happening._

Id the sample size is bigger the results become more accurate and fit better into the normal distribution

**Question 7**

_Why is the sampling distribution not the "true" distribution?_ 

Because the model is not complete, different assumptions have been taken, which derives in different predictions that might alter the results. And might not represent te actual sets of data

**Question 8**

_Describe the values of the function of random variables (the output) for which we might expect the model to be inaccurate. Quantify this inaccuracy by comparing the probability calculated with the assumed distribution with the frequency of similar values observed. Use the empty cell in Task 3 in the `Analysis.ipynb` file for computations._

_Hint: you can count the number of values in an array that conform to a specific boolean condition using_`sum(MY_ARRAY <= MY_VALUE)`. _It may also be useful to find the length of an array with `len(MY_ARRAY)`._

The predictions done between 0.0-0.2 and 0.4-0.5 of the thickness of the ice, show a nearly inadequate position.Everything between the 0.2-0.4 has the most accuracy with the middle of the graph being the most accurate. 

**Question 9**

_Test your learning for this week! Do **Exercise 2** on the **Q1 Exam from 2023**, which you can download using [this link](https://mude.citg.tudelft.nl/2024/files/Exams/23_Q1.pdf)._

You can write your answer on a separate piece of paper; it is good practice for the exam.

**End of file.**

<span style="font-size: 75%">
&copy; Copyright 2024 <a rel="MUDE" href="http://mude.citg.tudelft.nl/">MUDE</a>, TU Delft. This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">CC BY 4.0 License</a>.