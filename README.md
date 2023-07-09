# Selecting_best_intern
readme:
Before running the code the sheet file should be downloaded in the csv format.
install pandas
The code provided performs the following steps:

1. Retrieves the dataset from the CSV file and stores it in the DataFrame df.
2. Performs data preprocessing by removing rows with missing values.
3. Defines the evaluation criteria weights in the criteria_weights dictionary.
4. Filters the DataFrame df to include only the desired streams and availability for a full-time internship.
5. Further filters the DataFrame based on performance scores in the 'Performance_10', 'Performance_12', and 'Performance_UG' columns.
6. Calculates the score for each intern based on the defined criteria weights.
7. Ranks the interns based on their scores in descending order.
Prints the top-ranked intern.
Overall, this code aims to filter and rank the interns based on specified criteria and select the top-ranked intern for further consideration.
Suggestions: Can be automated on downloading the sheet file in CSV format. 
The code can select the best intern if the data is pre-processed.
Suggestion on picking 5-10 candidates after this code and conducting the interviews and selecting the intern, the code may mislead or lose good candidates.

