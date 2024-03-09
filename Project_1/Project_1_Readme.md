## Problem Statement

  The proposed analysis involves a thorough examination of American College Testing (ACT) scores and participation rates across   
  various states in the U.S. from 2017 to 2019. It aims to identify trends at the national level, observing shifts in 
  participation and performance. At the state level, the focus is on discerning significant changes in scores and participation. 
  For 2017, there's an additional emphasis on section-wise performance, including English, Math, Reading, and Science, to  
  pinpoint strengths and weaknesses within states. The study also intends to contrast states with high and low participation  
  rates to explore potential correlations with composite scores. 
  Furthermore, it seeks to provide educational insights, offering guidance to policymakers on areas needing more attention. To     make the findings clear and engaging, especially for those not well-versed in technical details, the study emphasizes the use  
  of data visualization techniques, presenting trends, comparisons, and key insights in a user-friendly manner.

## Background

  The SAT and ACT, standardized tests long used in U.S. college admissions, have evolved since their introductions in 1926 and 
  1959, respectively, to align better with high school curricula and college readiness. Beyond admissions, these scores play a 
  role in scholarship eligibility, course placement, and even influence university rankings. However, they have sparked debates 
  over fairness and accessibility, with critics pointing out socioeconomic disparities and cultural biases that could skew 
  results. The test-optional movement, advocating for making these scores optional in admissions, gained momentum, especially 
  during the COVID-19 pandemic, leading many colleges to revise their testing requirements. The focus on these tests has also 
  affected high school education, often emphasizing test preparation in the curriculum. Recent research questions their 
  predictive validity, suggesting that high school GPA might be a more accurate indicator of college performance, advocating for 
  a more holistic approach in admissions. Furthermore, there are concerns about how these tests affect diversity in college 
  admissions, with some studies indicating that they might disadvantage certain groups. This scenario reflects the ongoing 
  complexities and discussions surrounding standardized testing in the educational landscape.
  
https://www.apguru.com/blog/the-impact-of-sat-and-act-scores-on-college-admissions

https://civilrightsproject.ucla.edu/news/research/college-access/admissions/the-role-of-standardized-tests-in-college-admissions

https://blog.prepscholar.com/the-history-of-the-act-test

## Data Dictionary

ACT 2017 Data
- Columns: State, Participation, English, Math, Reading, Science, Composite
- Data Types: State (object), Participation (object), English (float64), Math (float64), Reading (float64), Science (float64),  
  Composite (object)
- Number of Entries: 52
- Example Data:
  - State: National, Participation: 60%, English: 20.3, Math: 20.7, Reading: 21.4, Science: 21.0, Composite: 21.0

ACT 2018 Data
- Columns: State, Participation, Composite
- Data Types: State (object), Participation (object), Composite (float64)
- Number of Entries: 52
- Example Data:
  - State: Alabama, Participation: 100%, Composite: 19.1

 ACT 2019 Data
- Columns: State, Participation, Composite
- Data Types: State (object), Participation (object), Composite (float64)
- Number of Entries: 52
- Example Data:
  - State: Alabama, Participation: 100%, Composite: 18.9

The 2017 dataset is more detailed with scores for English, Math, Reading, and Science, while the 2018 and 2019 datasets focus on overall composite scores and participation rates.

## Summary of the analysis

Based on the research, there have been some noteworthy developments and policies regarding the ACT testing in various states in  
the U.S. during 2017-2019.

- State Requirements for ACT/SAT: As of 2019, 25 states required students to take the SAT or ACT, a number that remained steady 
  from 2016 and 2017. This trend marked a significant increase from a decade earlier, reflecting a broader effort by states to  
  encourage college readiness and application among high school students.
https://www.edweek.org/teaching-learning/what-tests-does-each-state-require/2017/02.

- Statewide Testing and ACT Preparation: For states that have mandated ACT testing, various resources and support systems are  
  often   made available to students. This includes the opportunity for students to take the test for free, access to in-class 
  preparation, and other free preparation materials. However, the quality of these materials and the level of preparation can  
  vary, and it's advisable for students to independently verify any test-related information they receive.
https://blog.prepscholar.com/which-states-require-the-act-full-list-and-advice

- Impact of COVID-19 on Testing: The COVID-19 pandemic posed significant challenges to the educational ecosystem, including the 
  process of learning and testing. ACT research highlighted the various impacts of the pandemic on students, noting disruptions  
  in 
  traditional learning environments and the necessity for educational institutions to adapt to these changes. The pandemic also 
  affected students' social and emotional well-being, influencing their academic preparedness and performance on standardized  
  tests like the ACT.
https://www.act.org/content/act/en/research/reports/act-publications/impact-of-covid-19-on-learning-and-testing.html

- State-by-State ACT Scores and Participation: There were notable differences in ACT scores and the percentage of graduates 
  taking 
  the test across states between 2015 and 2019. States like Illinois and Kentucky saw 100% participation rates in certain years, 
  while other states like Maine and New Hampshire had significantly lower participation rates but higher average scores. This 
  variance indicates the diverse educational landscapes and policies across the U.S. states.
https://nces.ed.gov/programs/digest/d19/tables/dt19_226.60.asp

## Conclusions and Recommendations

The exploration of the data provides several key takeaways:
- Participation Rates vs. Scores: There is a clear negative correlation between participation rates and average scores across all  
  subjects. Higher participation rates often correspond with lower average scores. This could be due to a wider range of  
  abilities   among test-takers, as mandatory testing policies may include students less prepared for the test.
  
- Score Consistency Across Subjects: There is a strong positive correlation between scores across different subjects. Students  
  who perform well in one subject tend to do well in others, indicating a consistent level of education across subjects within  
  states.
  
- Variability in Scores: States with low participation rates display a greater variability in scores. This could point to a  
  significant difference in the educational environment or student preparedness between these states.
  
- Composite and Total Scores: The relationship between composite and total scores is linear, but the total score distribution 
  shows   a greater spread. This suggests that while both are aggregate scores, they may be calculated or scaled differently.

Based on these observations, here are some recommendations:
- Educational Policy: States with lower participation rates and higher variability in scores might benefit from policies aimed at   improving access to quality education and test preparation resources. This could help raise the lower end of the score     
  distributions.
  
- Targeted Interventions: The negative correlation between participation rates and scores suggests a need for targeted 
  interventions to support students who are currently underperforming. Programs that offer additional tutoring or resources could   be particularly beneficial.
  
- Further Research: The reasons behind the wider variability in scores among states with low participation rates warrant further   investigation. Research into the educational systems, socioeconomic factors, and state-level policies could provide insights  
  into how to improve scores.
  
- Score Analysis for Policy: The differences in score distribution between high and low participation states should be considered 
  when using these scores to inform educational policy. It is important to account for the broader range of abilities and  
  preparation levels among students.
  
- Caution in Interpretation: When interpreting test scores for making decisions at the state level, it's important to consider 
  participation rates. Comparisons between states should account for the potential impact of different rates of participation on   the scores.
  
Overall, the data suggests that while there is consistency in performance across subjects within states, the effect of participation rates on average scores is significant and should be taken into account in policy-making and educational strategy.

