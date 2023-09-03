# Astronaut-Data-Analysis-Report
This Python code is designed to read astronaut data from a CSV file and generate a comprehensive data analysis report in the form of an Excel workbook. The code utilizes the Pandas, Seaborn, and Matplotlib libraries for data manipulation, visualization, and report generation. The resulting Excel file contains multiple sheets.

Description:

This Python code is designed to read astronaut data from a CSV file and generate a comprehensive data analysis report in the form of an Excel workbook. The code utilizes the Pandas, Seaborn, and Matplotlib libraries for data manipulation, visualization, and report generation. The resulting Excel file contains multiple sheets, each presenting different aspects of the astronaut data and associated plots.

Code Overview:

Data Reading: The code begins by reading astronaut data from the specified CSV file using Pandas and stores it in a DataFrame.

Random Samples: A sheet named "Random_Samples" is created, containing five randomly selected samples from the dataset. These samples provide a quick overview of the data.

Data Preparation: Certain columns in the dataset, such as "days in space," "spacewalks," "days spacewalking," and "missions," are converted to numeric data types. This ensures that these columns are treated as numerical values for analysis.

Astronauts Still in Space: A sheet named "Astronauts_In_Space" is created, containing information about astronauts who are currently in space based on the "still in space" column.

Country-wise Analysis: The code generates a sheet named "Country_Wise_Astronauts" that provides a count of astronauts from each country in the dataset. Additionally, it calculates and displays the total days astronauts from each country have spent in space.

Highest Number of Missions: A sheet named "Highest_Missions_By_Country" is created to showcase the countries with the highest number of missions. It displays the top countries with the most missions.

Numeric Conversion Columns: A sheet named "Numeric_Conversion_Columns" is created to list the columns that were converted to numeric data types.

Space Agency Analysis: The code analyzes the number of unique space agencies by country and creates a sheet named "Space_Agencies_Country_Wise" to display this information.

Missions by Space Agency: A sheet named "Missions_Space_Agency_Wise" presents the total number of missions carried out by each space agency.

Plotting: For specific sheets related to country-wise analysis, space agencies, and missions, the code generates corresponding bar plots using Seaborn and Matplotlib. Each plot is saved as a separate image file and then inserted into the Excel file.

Conclusion:

This code allows for a thorough analysis of astronaut data and presents the results in an organized Excel report with descriptive plots. Users can gain insights into various aspects of astronaut missions, including country-wise contributions and mission statistics.
