# Kickstarting with Excel
    Keith Rabb 281-513-5996 keithrabb@icloud.com
## Overview of Project
    Louise is interested in how other kickstarter projects (crowdfunding) did with respect to launch dates and funding goals when trying to fund plays.
### Purpose 
    To visualize campaign outcomes based on their launch dates and funding goals.
## Analysis and Challenges
#### Analysis Observations
- May and June have higher numbers of launch dates compared to other months, but their failure rate during those months is also high.
- Only four months of the year in this data set were NOT above 60% for successful crowdfunding outcomes - Dec, Jan, Aug, and Oct

- Crowdfunding projects under $5K had the highest success rate for funding.
- 73% Chance of being funded in the $1K to $5K range. 76% chance under $1K. 
- Plays with a budget range from $5K to $25 have approximately 50% chance of funding.
- Failure rate for crowdfunding projects above $45K is almost assured.
### Analysis of Outcomes Based on Launch Date
![Theater_Outcomes_vs_Launch](Resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
![Outcomes_vs_Goals](Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

#### The goal ranges are fairly broad when trying to pinpoint a target for budget, thus needing granularity to find "best chance for success".
- Establish a smaller range within a range for the data set.
- Establish a reasonable quantified target amount to expect for future crowdfunding a projects.

#### The below chart shows that within the range of $1K to $5K, the MEAN is just under $2500
#### Upper quartile is $3.2K and the lower quartile $1.6K
![Mean_of_success_predicted_target](Mean_of_success_predicted_target.png)
    
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
    - Do not launch crowdfunding before or after Christmas, during back to school, or before Thanksgiving.
    - May and June have the highest numbers of successful outcomes but the average throughout all months is fairly consistent.
- What can you conclude about the Outcomes based on Goals?
    - The "sweet-spot" for crowdfunding is in $1K-$5k range, but specifically $1.6K-$3.2K, with a mean of almost $2.5K
- What are some limitations of this dataset?
   - There is nothing to compare other trends such as spending habits, environmental factors, psychological factors to give us more insight to spending/crowdfunding behavior.   
- What are some other possible tables and/or graphs that we could create?
    - The box-plot above seemed almost necessary to me and I considered a table of averages to further explain the data.
