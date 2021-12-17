# Kickstarter Analysis
## Performing analysis on Kickstarter data to uncover trends
### Project Overview:
The purpose of this analysis was to analyze data on campaigns ran on the website Kickstarter.  The requestor is planning on launching a Kickstarter campaign to raise funds for a theater production.  The bulk of the analysis focused on similar campaigns for theater related projects, primarily in the US and Great Britain.

### Analysis and Challenges:
The analysis began with reviewing what was in the data set and what could be calculated from the fields provided.  The "Percentage Funded" and "Average Donation" fields were calculated using data provided.  The "Category and Subcategory" field was broken down into two fields to allow filtering at a more granular detail.  Lastly, the "Date Created" and "Date Ended" fields provided were converted into a more readable format and a field for the "Year" was created.

After all the new fields that were needed were added, separate pivot tables at the "Category" and "Subcategory" were created to filter and view the data specific to theaters and plays.  Another pivot table was created to see the relationship between launch date and project outcome.  Also, analysis on specific project was performed on plays that were showing at a film festival in Edinburgh.  

Lastly, a pivot table was created to review project outcome by the goal of the project.  This required breaking the goal down into different dollar amount ranges.  Upon review of this table it was determined there were some outliers in the data.

### Results:
The below chart represents the project outcome for projects vs their launch date.
Conclusion 1: There is a spike in successful projects in May and June.
Conclusion 2: January had the most canceled projects.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/95188079/145723990-d098cd26-1ab7-4972-a1e9-b280d36b5993.png)


The below chart represents the project outcome vs the goal.
Conclusion 1: The highest percentage of successful projects were in the "Less than 1000" and "1000 to 4999" ranges.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/95188079/145723996-6db766f2-4535-4124-80f2-7ce8fee9f771.png)


One limitation on the data set it lack of data on the project owner, including how many previous Kickstarter campaigns they had and their outcomes.  There could perhaps be a trend of someone failing on their first campaign but succeeding on later ones.  Additional graphs could be created to project outcome to either average donation amount or number of backers.






