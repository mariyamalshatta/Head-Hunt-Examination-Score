# Head-Hunt-Examination-Score
Estimate the average examination score and validate a critic claim

**Business Context**

A research institute conducts a Talent Hunt Examination every year to hire people who can work on various research projects in the field of Mathematics and Computer Science. A2Z institute provides a preparatory program to help the aspirants prepare for the Talent Hunt Exam. The institute has a good record of helping many students clear the exam. Before the application for the next batch starts, the institute wants to attract more aspirants to their program. For this, the institute wants to assure the aspiring students of the quality of results obtained by students enrolled in their program in recent years.

However, one challenge in estimating an average score is that every year the exam’s difficulty level varies a little, and the distribution of scores also changes accordingly. The institute keeps a track of the final scores of its alumni who attempted the exam previously. A dataset constituted of a simple random sample of final scores of 600 aspirants from the last three years is prepared by the institute.

**Objective**

The institute wants to provide an estimate of the average score obtained by aspirants who enroll in their program. Keeping in mind the variation in scores every year, the institute wants to provide a more reliable estimate of the average score using a range of scores instead of a single estimate. It is known from previous records that the standard deviation of the scores is 10 and the cut-off score in the most recent year was 84.

A recent social media post from A2Z institute received feedback from a reputed critic, mentioning that the students from A2Z institute score less than last year's cut-off on average. The institute wants to test if the claim by the critic is valid.

**Solution Approach**

To provide a more reliable estimate of the average score using a range of scores instead of a single estimate, we will construct a 95% confidence interval for the mean score that an aspirant has scored after enrolling in the institute’s program.
To test the validity of the critic's claim (the mean score of the students from A2Z institute is less than last year’s cut-off score of 84), we will perform a hypothesis test (taking alpha = 5%)

**Data**

The dataset provided (Talent_hunt.csv) contains the final scores of 600 aspirants enrolled in the institute’s program in the last three years.
