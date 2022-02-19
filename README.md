# Kickstarting with Excel

## Overview of Project
We will use the Kickstarter data to analyze what the different data sets reveal about trends in Crowdfunding focusing on outcomes based on
launch date and outcomes based on goals.

### Purpose
The objective of this project is to provide our client, Loiuse, with a better ability to see how other campaigns did in relation to their launch date
and funding goals.  This will allow her to make the most informed decision about her campaign in Crowdfunding.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
I started the analysis by thoroughly going over the dataset to familiarize with all the different data points.  I found I could expand on existing
information to make the data better reflect our goals.  I then began to narrow down what data we would need to help Loiuse.  I created a pivot chart to show only theatre campaigns that succedded, failed, or canceled and to sort by month. This allowed me to have all relevant data to analayze the effect launch date has on outcome.
![Threatre Outcomes vs Launch](https://user-images.githubusercontent.com/97993428/154818428-e3545cb3-bdd8-44af-b5f7-82026e69da97.png)
I concluded by the Threatre Outcomes by Launch Date that the vast majority of campaigns launched in May or June succeed at much higher rates than any other months, and they fail at a only slighter higher than average rate than other months.  I can also conclude that the worst two months for a successful campaign is November and December with the highest probability of failure if you launch in December.  The likelihood of failing in December is 95% and the likelihood of failure in November is 57%.

### Analysis of Outcomes Based on Goals
To analyze the outcomes based on goals better, I broke the donation amounts down into smaller, more manageable amounts.  I then narrowed outocmes to only those that were finished.  I was then able to have a clearer data set to show what campaign goal amounts had the highest chances of success or failure.![Outcomes_Vs_Goals](https://user-images.githubusercontent.com/97993428/154818960-73dad118-b17f-4986-9df3-99f8edfe902d.png)
From the Outcomes Based on Goals, the best chances of success are with campaigns on the far ends of the spectrum with the lower end of campaign goals reaching their target at lest 76% of the time.  For campaigns requesting less than a $1000 or reaching their goal 76% of the time,  and the greatest chance of success if your campaign is requesting  $1000 or greater but less than $5000 reaching their goal 86% of the time.  At the other end of the spectrum is campaigns requesting greater than $50000 at 67% of the time while the average of all other months is only 6%.  

### Challenges and Difficulties Encountered
The only real challenge was working through excel and troubling shooting when I couldn’t get the numbers or charts to work.  I found that as long as I kept researching the formula and playing with the different elements within the formula I could get it done.  The countifs() function gave me the most difficulty, but I watched numerous turtorials and was able to conquer it. 

## Results

Based on this analysis, I believe the data shows that the best launch month as May and the worst launch month as December.  Simultaneously, the best campaign goal for success is requesting greater an $1000.00 but less than $5000.  Some limitations of the dataset is that we are given limited information.  We have no data on marketing done to promote certain campaigns or how many people came across the campaigns in general.  In order to maximize her campaign’s ability to succeed it would help to also have data on what other campaigns did to increase visibility such as ads or social media sharing.  An additional graph could be made to show amount of socila media shares and how they affect the campaign outcome.
