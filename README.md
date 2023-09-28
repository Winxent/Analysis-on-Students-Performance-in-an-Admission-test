# Students Performance in an Admission test
Goal: A school wants to analyze how parental education level and test preparation courses would affect a student's academic performance?

![rainbow](https://github.com/Winxent/portfolio/assets/146320825/5dc438d2-e138-4db0-97a0-e5ae8c3473e8)

# Introduction
Many students take admissions tests, and they encounter various difficulties. Understanding and analyzing student performance on those examinations is vital for schools to determine how they may contribute to improving it.  The performance of students might fluctuate amongst groups and be impacted by a variety of circumstances. A deeper comprehension of these elements can aid the school in developing methods to raise student achievement.

![rainbow](https://github.com/Winxent/portfolio/assets/146320825/5dc438d2-e138-4db0-97a0-e5ae8c3473e8)

# Data Description
<img width="1165" alt="image" src="https://github.com/Winxent/Analysis-on-Students-Performance-in-an-Admission-test/assets/146320825/912cf6b5-192f-49e2-ab64-e0f5f9cb23ba">


There are 1000 rows and 9 columns in this dataset. Since there were no null values in this dataset, no data imputation was utilized during data preprocessing. 

Both categorical and numerical column types are used to display data about the students, including gender, test preparation courses taken, parental education level, lunch, race/ethnicity groups, and scores on the writing, reading, and math sections of the admission test. 

We also have a feature-engineered column called Obtained Score, which is a score total. Students' scores in the various portions of the test as well as the overall score are provided in numerical columns. However, categorized columns are giving us some further information about their background and exam preparation that can aid in our research. 

![rainbow](https://github.com/Winxent/portfolio/assets/146320825/5dc438d2-e138-4db0-97a0-e5ae8c3473e8)

# Methodology for Data Analysis:
We have used many data analysis approaches, such as 
1. Data aggregation and Data summary procedures, to filter our dataset into subsets and aggregate it using either the mean, mode, or median. 
2. To do our data aggregation based on quartiles, we have conducted analysis using the Minimum, Maximum, and Range values of the numerical columns. We were able to do an inter-quartile range analysis using these quartiles to identify outliers in a dataset. 
3. In addition to putting Measures of Location and Measures of Spread into practice, we also performed data visualization analysis by creating scatter plots, bar plots, and correlation graphs from our dataset. 

![rainbow](https://github.com/Winxent/portfolio/assets/146320825/5dc438d2-e138-4db0-97a0-e5ae8c3473e8)

# Insights Generation:
Here are some conclusions we were able to draw from the aforementioned analysis: 

### Depending on gender
Female students were able to perform better than male students when comparing their overall performance on the admissions test based on Obtained Score. 
However, if we look at the individual results, we find that female students did not perform any better than male students in math. However, they performed better in writing and reading than the study's male participants.

<img width="623" alt="image" src="https://github.com/Winxent/Analysis-on-Students-Performance-in-an-Admission-test/assets/146320825/a84f579d-975a-4c38-8221-ba039456e4cc">

### Based on exam preparation: 
According to overall scores and section-by-section scores, all students who were able to finish the test preparation courses were performing relatively better than other students. 

<img width="628" alt="image" src="https://github.com/Winxent/Analysis-on-Students-Performance-in-an-Admission-test/assets/146320825/ceb79659-6179-4f1f-adb0-d7df212b7009">

### Based on Parental Education Level:
We summed up our analysis at Parental Education Level in order to help you comprehend the significance of your parents' educational background. 
In comparison to students whose parents had some college or some high school as their parental level of education, those whose parents had significantly higher levels of education, such as Masters or bachelors, were able to earn decent grades. 

<img width="635" alt="image" src="https://github.com/Winxent/Analysis-on-Students-Performance-in-an-Admission-test/assets/146320825/a50bb2ed-0d51-4f49-85c7-c2bb4fbdb144">

### Performance by section: 
We have determined that students have struggled the most in the Math part compared to other sections based on the minimum, mean, and median scores in the Math portion. 

<img width="252" alt="image" src="https://github.com/Winxent/Analysis-on-Students-Performance-in-an-Admission-test/assets/146320825/0bc53d14-22fd-4981-ba0a-d639f5802ed6">


### Identification of Outliers: 
Using the Interquartile Range, we were able to pinpoint two students who scored below either the IQR minimum or the bottom bound of the data distribution. 

<img width="378" alt="image" src="https://github.com/Winxent/Analysis-on-Students-Performance-in-an-Admission-test/assets/146320825/6067ed91-d226-4bfa-92be-6427f052ec14">

![rainbow](https://github.com/Winxent/portfolio/assets/146320825/5dc438d2-e138-4db0-97a0-e5ae8c3473e8)

# Conclusion
1. We now know that parents play a substantial part in a student's performance improvement. Parents who are educated, for instance, who hold a bachelor's or master's degree can better inspire and prepare their children for the admissions test. For parents who don't have a lot of education, schools can also set up extra help and training courses. so that these parents can inspire their kids and contribute more effectively to their achievement.
2. According to the dataset analysis, students who have completed test preparation classes can do better on all of the admissions exam's sections and earn higher grades. So that students can perform better on tests, schools should push them to finish preparation courses that allow them to practice all portions conceptually and practically.

<img width="787" alt="image" src="https://github.com/Winxent/Analysis-on-Students-Performance-in-an-Admission-test/assets/146320825/12c75db7-f6b9-4878-b914-08601d4ab821">







