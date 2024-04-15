# Accenture-North-America-Data-Analytics-and-Visualization-Job-Simulation-
Accenture North America Data Analytics and Visualization Job Simulation 
7 datasets and a data model.
Using this data model to identify which datasets will be required to answer your business question - which is to to figure out the top 5 categories with the largest popularity.
Identified Reaction, Content, and Reaction Types as our relevant data sets.
To clarify why you made this selection:

The brief carefully it states that the client wanted to see “An analysis of their content categories showing the top 5 categories with the largest popularity”.
As explained in the data model, popularity is quantified by the “Score” given to each reaction type.
We therefore need data showing the content ID, category, content type, reaction type, and reaction score.
So, to figure out popularity, we’ll have to add up which content categories have the largest score.

Clean the data by:
1. Removing rows that have values which are missing,
2. Changing the data type of some values within a column.
3. Removing columns which are not relevant to this task.

Data modelling :
1. Create a final data set by merging your three tables together.
2. Figure out the Top 5 performing categories.
