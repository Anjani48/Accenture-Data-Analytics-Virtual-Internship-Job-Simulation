# Accenture-Data-Analytics-Virtual-Program

For the Project
The client has sent through:
•	7 data sets - each data set contains different columns and values
•	A data model - this shows the relationships between all of the data sets, as well as any links that can use to merge tables.
For these need to follow the below steps:
1.	Requirements gathering
2.	Data cleaning
3.	Data modelling
Data sets :
   ->Reaction, Content, and Reaction Types as data sets.
To clarify why these selection has made:
•	The brief carefully it states that the client wanted to see “An analysis of their content categories showing the top 5 categories with the largest popularity”.
•	As explained in the data model, popularity is quantified by the “Score” given to each reaction type.
•	It need to data show the content ID, category, content type, reaction type, and reaction score.
•	So, to figure out popularity, adding up the content categories which have the largest score.

Second: Clean the data by:
•	removing rows that have values which are missing,
•	changing the data type of some values within a column, and
•	removing columns which are not relevant to this task.

 
At end result should will be three cleaned data sets. 
Now we finding the top 5 categories,to complete the data modelling, follow bt the steps:
1. Creating a final data set by merging your three tables together
•	Taking Reaction table as base table, then at first joining the relevant columns from Content data set, and then the Reaction Types data set.
•	By using “VLookUp” formula.
 
2. Figuring out the Top 5 performing categories
•	Add up the total scores for each category.
•	By using “Sum If” formula.

At,the end result will be one spreadsheet which contains:
1.	A cleaned dataset
2.	The top 5 categories


