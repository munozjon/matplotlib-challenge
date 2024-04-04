# matplotlib-challenge

## Module 5 Challenge

For this challenge, I joined the pharmaceutical company, Pymaceuticals, Inc., in order to generate tables, figures, and summarize the results from a clinical study performed on mice with squamous cell carcinoma (SCC). The objective of the study was to compare the performance of the drug regimen Capomulin against other treatments for this form of skin cancer. The study was conducted on 249 mice over 45 days, where the development of the SCC tumors were observed.

I was provided with the study's results on different CSV files. Using different statistical Python libraries and modules, I successfully analyzed and visualized the results of the study below. Here are the observations I made:

## Observations and Analysis

### Trends from the Overall Study

Before looking at the overall summary of the study, it is important to notate that the sex of the mice observed was generally even, with a slight male skew (51%). In addition, a female mouse on Propriva was identified and removed from the study to ensure a clean dataset.

In observing the data, we can see that Capomulin and Ramicane were the drug regimens that were most observed in terms of the number of mice. Furthermore, they each had the lowest average tumor volume (about 40.68 and 40.22 mm3 for Capomulin and Ramicane, respectively) of all the drug regimens in the study. The same can be said about the median, variance, and standard deviation of their tumor volumes. Each statistical result proved to be significantly lower than the rest of the drug regimen, showcasing the consistent effectiveness of these drug regimens in particular.

### Comparing Capomulin to Ramicane and Other Regimens

Further analyzation of Capomulin, Ramicane, Infubinol, and Ceftamin drug regimens yield interesting results. When comparing the last timepoint for each mouse on these regimens, we can see that, as was the case above, the mice on the Capomulin and Ramicane regimens had lower tumor volumes than the mice on Infubinol and Ceftamin. In the case of Infubinol, there was a notable outlier below the lower bound of the regimen's boxplot; none of the other drug regimens had any statistical outliers. Despite this outlier, the lower bounds for Infubinol and Ceftamin were around the same volume size of the upper bounds for Capomulin and Ramicane, further demonstrating the effectiveness of the latter two in particular.

Between Capomulin and Ramicane, their boxplots were very similar. However, Ramicane's median and overall range of its data was less than Capomulin. This serves to emphasize that Ramicane is a better performing drug regimen than Capomulin. This is further helped by the statistical summary results, where the average, median, variance, standard deviation, and standard error for the mice on Ramicane were all slightly less than the ones for the mice on Capomulin. While both appear to be very effective compared to other drug regimens, it is Ramicane that slightly edges out Capomulin as the one that yeilds better results.

### Trends in the Capomulin Drug Regimen

Analyzing the drug regimen Capomulin by itself generates notable statistical results. When seeing the trend in tumor volume for a mouse over the course of the study, we notice that the size fluctuates, but generally decreases over time. This serves to further prove its effectiveness in treating the tumor. Moving forward, when comparing the weight of the mice on Capomulin and their average tumor size, there is a noticable positive correlation. With a correlation coefficient of about 0.84, it can be said that the weight of the mice and the size of their tumor have some relationship to each other. It should be noted that this does not necessarily mean that the size of the tumor is caused by their weight. Despite this, there is a clear association between the two.

## Conclusion

Overall, the study was able to successfully show that Capomulin was effective in treating SCC tumors. Despite Ramicane performing slightly better, it should be noted that Capomulin was still able to outperform all the other drug regimens. Further studies can be done to show the effects of the regimens over a longer period of time. In addition, analyzing the results by the sex or the age of the mice can provide even more context and give Pymaceuticals, Inc. more data on the performance of Capomulin.