# School_District_Analysis
Challenge 4:

For module four, we looked at reading and math test scores in a school district and compared them between all the schools in the district. The school board wanted the data to see how each school in the district fared against one another to find out which schools tested better and which ones did not. Through out the module, we cleaned and organized to make the data look presentable. We cleaned both the school data and the student data and merged them together to get one big dataframe to analyze the data. At the end of the module, we were told that we needed to replace the test score data to fairly judge one of the schools, Thomas High School 9th graders, because they think there could be some academic dishonesty when it came to the test scores. 

The first thing we did for this challenge was take the test scores for the 9th graders at Thomas High School and replace them with NaN because of the thought of academic dishonesty. We wanted to make sure that those test scores would not have an impact on the final numbers outcome because they were not reliable. After we were finished replacing those test scores, we remade all of our dataframes that we did during the module to reflect the changes.

•	The district summary wasn’t that all affected by the changes of the test scores for the ninth graders at Thomas High School. The rankings didn’t change at all. Thomas High School still comes in as the number two school when ranked by their overall passing percentage. In the original coding we did in the module, the passing percentage for Thomas high school was 90.95% when we replaced the scores their overall percentage dropped to 90.63%.

Overall Passing with 9th Grade Scores: ![](Images/fig1%20with%20scores.PNG)

Overall Passing without 9th Grade Scores:![](Images/fig2%20without%20scores.PNG)


•	As far as the school summary the biggest we can see is the changes in the average score. I see there was an increase in the average reading score from 83.84% to 83.89% and a decrease in the average math score from 83.41% to 83.35%. The only conclusion I can come up with for that reason would be that the nineth grade average reading scores could have been dragging down the entire school. Now that the scores are not in there, the average went back up. 

Math and Reading Average with scores: ![](Images/fig3%20average%20scores%20with.PNG)

Math and Reading Average without 9th Grade scores: ![](Images/fig4%20average%20without.PNG)


•	The overall percentage didn’t really change the ranking for Thomas High School when ranking the best schools. The only difference was that Thomas high school overall percentage was down .3% after the nineth grade scores were taking out. 

Top schools ranked by Overall PAssing Percentage with THS 9th Grade scores : ![](Images/fig%205%20top%20schools%20with.PNG)

Top schools ranked by Overall PAssing Percentage without THS 9th Grade scores : ![](Images/fig6%20top%20schools%20without.PNG)

•	As far as breaking down the data by the grade, spending, size and school type there really is no difference except in the scores by grade and that’s because the math and reading grades were removed from the 9th grade at Thomas High School.

Math scores with THS 9th Grade Scores :![](Images/fig7%20math%20with.PNG)

Math scores without THS 9th Grade Scores: ![](Images/fig9%20math%20without.PNG)

Reading scores with THS 9th Grade Scores :![](Images/fig%208%20reading%20with.PNG)

Reading scores without THS 9th Grade Scores: ![](Images/fig10%20reading%20without.PNG)


When we updated the scores, I thought there would have been a dramatic difference in the rankings and all the numbers. But as we saw, there really wasn’t much of an impact when removing the 9th grade reading and math scores from the analysis. The biggest difference that was seen was the drop in overall passing percentage, but even that was less than half a percentage point. 
