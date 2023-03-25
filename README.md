# Pymaceuticals Inc.
---

## Analysis

### Summary 

After analysis of the provided data for 248 mice, treated with 9 different drug regiments and 1 placebo, we can drow conclusion that the mice which were treated with the Pymaceuticals’ drug of interest, Capomulin, have shown a good response against the other treatment regimens. Other drug regimen that had good results was Ramicane. The mice treated with the Capomulin and the Ramicane have shown reduction of the tumor size. 


!['Tumor volume for each treatment group'](https://user-images.githubusercontent.com/122633144/227735930-870b4df0-a701-42cf-955f-ca038343c4c5.png)


!['Average Tumor Volume vs  Mouse Weight For The Capomulin Regimen'](https://user-images.githubusercontent.com/122633144/227735937-a02512e8-81e8-49aa-9ae0-60fd3e2ac9d5.png)


### Data collection and preparation

For this analysis was used data provided by the most recent Pymaceuticals’ animal study. After merging the data into one data frame and getting the unique values for every mouse, we found that there was one duplicate Mouse ID which was dropped from the original data, and we continued working with the clean data that we now had. The distribution of female versus male mice was 49% vs. 51%.


!['Female Vs  Male Mice Distribution'](https://user-images.githubusercontent.com/122633144/227735916-0b630f42-a848-4dc6-9b94-c468c2661c44.png)


### Analysis methods

In this analysis were used Python, Matplotlib, Jupyter Notebook, Pandas and Statistics.



NOTE - In the part where we calculate the quartiles and IQR, and determine if there are any potential outliers across all four treatment regimens, I was working with the AskBCS LEarning Assistant on Slack. They helped me clean my code and build the loop.
