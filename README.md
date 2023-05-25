# pandas-challenge (Module 4 Challenge)
Note: This is a daily diary of work on homework including the files that were used as sources or the individuals who I worked with.

5/21 
Started with PyCitySchools_starter.ipynb
Short study group with Eva, Tracy and Tahseen - just talked about some logistics and moral support

For District Summary: count unique schools: https://www.geeksforgeeks.org/how-to-count-distinct-values-of-a-pandas-dataframe-column/
to get unique budget first made a new dataframe with just the schools
https://sparkbyexamples.com/pandas/pandas-create-new-dataframe-by-selecting-specific-columns/
then deleted duplicates followed by summing the budget

For School Summary
Note: the first input stated to “use the code provided…” but there was no code so used .unique()
https://sparkbyexamples.com/pandas/pandas-find-unique-values-from-columns/#:~:text=You%20can%20get%20unique%20values,to%20get%20from%20multiple%20columns.

Changing a count to dataframe and resetting index
https://stackoverflow.com/questions/47136436/python-pandas-convert-value-counts-output-to-dataframe
https://stackoverflow.com/questions/20461165/how-to-convert-index-of-a-pandas-dataframe-into-a-column
merged the two df’s by referencing merging_solutions exercise

Math - dividing between two columns for per_capita https://linuxhint.com/divide-two-columns-pandas/

5/23
looked up to remove rows based on condition https://stackoverflow.com/questions/13851535/how-to-delete-rows-from-a-pandas-dataframe-based-on-a-conditional-expression - WORKED!
Used groupby for the per school calculations and the code provided in the starter file
Feel like I have a complicated solution for the % by school calc but will come back to it on Wed.

5/24
- Referred to Day 3 crowdfunding_cleaning to reduce columns using loc
-For by school summary https://pythonguides.com/add-a-column-to-a-dataframe-in-python-pandas/
- When starting to make the school summary, I realized that I needed the type of school for each school. There was no code provided (even though stated) so I decided to make a dataframe and sort it alphabetically by school so that it lines up with the other ones that I want to combine from. https://www.statology.org/pandas-sort-alphabetically/
- deleting columns help: https://stackoverflow.com/questions/13411544/delete-a-column-from-a-pandas-dataframe
- For Math Scores by Grade section I got assistance from Tasheen in study group to set up how to pull the mean for the math scores in the subgroup.
- For Scores by School Spending section had to pull the raw numerical data for the "Per Student Budget" - thanks for the hint by Eva in study group
- Adding a title to index https://sparkbyexamples.com/pandas/pandas-set-index-name-to-dataframe/


