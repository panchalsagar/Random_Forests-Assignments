# Random_Forests-Assignments

# Problem - 1


About the data: 

Let’s consider a Company dataset with around 10 variables and 400 records. 

The attributes are as follows: 

1.  Sales :- Unit sales (in thousands) at each location

2.  Competitor Price :- Price charged by competitor at each location

3.  Income :- Community income level (in thousands of dollars)

4.  Advertising :- Local advertising budget for company at each location (in thousands of dollars)

5.  Population :- Population size in region (in thousands)

6.  Price :- Price company charges for car seats at each site

7.  Shelf Location at stores :- A factor with levels Bad, Good and Medium indicating the quality of the shelving location for the car seats at each site

8.  Age :- Average age of the local population

9.  Education :- Education level at each location

10. Urban :- A factor with levels No and Yes to indicate whether the store is in an urban or rural location

11. US :- A factor with levels No and Yes to indicate whether the store is in the US or not

The company dataset looks like this: 

Problem Statement :- A cloth manufacturing company is interested to know about the segment or attributes causes high sale. 

Approach :- A Random Forest can be built with target variable Sales (we will first convert it in categorical variable) & all other variable will be independent in the analysis.


# Problem - 2

Use Random Forest to prepare a model on fraud data treating those who have taxable_income <= 30000 as "Risky" and others are "Good"
