# Kickstarting with Excel

## Overview of Project

Performing analysis on Kickstarter data to uncover trends.

### Purpose

Louise wants to start a crowdfunding campaign on Kickstarter to help fund her play, *Fever*, and has asked us to perform an analysis to aid in deciding what factors contribute to providing a successful Kickstarter campaign.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

For an analysis of the outcomes of successful, failed, and canceled kickstarter projects that involved theater productions, I created a pivot table that broke down all the kickstarters and organized them by the number of successful, failed and canceled projects, as well as the month the project was started. That way we could easily visualize the data to see which months had the greatest and least number of successful outcomes, as well as failed outcomes. From there I made a line chart, pictured below, that helps to visualize the outcomes of the theater Kickstater campaigns.

![alt text](https://github.com/tmidcalf/kickstarter_challenge/blob/main/Resources/Theater_Outcomes_vs_Launch.png?raw=true)

### Analysis of Outcomes Based on Goals

In order to analyze the outcomes of Kickstarter campaigns based upon the target amount of money for the project, I first needed to organize the data. To do this, I grouped the number of successful, failed, and canceled projects into different money ranges. This way we can easily analyze the percentage of outcomes for all projects based upon how much money that project is asking for. From there I created a line graph, pictured below, that allows us to easily visualize the money ranges that resulted in successful campaigns as well as failed campaigns.

![alt text](https://github.com/tmidcalf/kickstarter_challenge/blob/main/Resources/Outcome_vs_Goals.png?raw=true)

### Challenges and Difficulties Encountered

Although I did not encounter any challenges analyzing this dataset, I could see that getting the correct criteria ranges for the COUNTIFS statements on the “Outcomes Based on Goals” sheet could provide some difficulties. It’s important that those criteria are entered correctly so that the range buckets display the appropriate information.

## Results

- According to the data from previous Kickstarter campaigns that involved theater productions, the month of May was found to be the month that yielded the most successful campaigns. Also, we can conclude, out of all the months, December seems to be the most difficult month to start a successful campaign, as that was the only month that we saw a larger number of failed projects than successful projects.

- From the data collected, we can see that the smaller the goal amount the more likely the chance the project will have a successful outcome. With Louise’s budget of over $10,000, she might want to set a goal of just under $10,000, as we can see that campaigns with a goal of $5,000 to $9,999 were successful more than half of the time.

- This data could be limited by some of the outliers that had unrealistic expectations that are present in the dataset. In fact, out of the 49 campaigns with a goal of $400,000 or more, only one project turned out to be successful. With that being recognized, it’s important to understand how some of these projects can limit and skew the data.

- Another chart or graph we could analyze could be how the data is distributed over each quartile along with a box and whisker plot to show where a majority of the data is distributed as well as describe where the outliers fall.
