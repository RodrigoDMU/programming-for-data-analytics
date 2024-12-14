# Higher Diploma in Science in Data Analytics
******

## Programming for Data Analytics Module

![Programming](ImgProgramming.jpeg)

************

## My Assessment Repository

This repository was created as part of the Programming for Data Analytics assessments module for the course in the [Higher Diploma in Science in Data Analytics](https://www.atu.ie/courses/higher-diploma-in-science-data-analytics?_gl=1%2A1bcdos0%2A_ga%2AMTE3OTU2MzQ5LjE2OTY2MDYwMzE.%2A_ga_5R02GBYV8V%2AMTcxNDMzOTE2Ni4xMS4xLjE3MTQzMzkyMDAuMC4wLjA.) at [ATU](https://www.atu.ie/). This README has been written with [Github's Documentation On READMEs](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes) in mind. You can find more about [writing in Mark Down in GitHub's documentation](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

## Getting Started

This repository contains my assessment submissions for the module, showcasing the skills I have developed throughout the course in data analysis, as well as my tasks and project.

*****

## Practical Assignments

*****

**- Assignment 2: Weather**

**Task description:** Create a jupyter notebook called [`assignment2-weather.ipynb`](https://github.com/RodrigoDMU/programming-for-data-analytics/blob/main/assignments/assignment2-weather.ipynb) that has a nice plot of the temperature over time
[`dryBulbTemperature_Celsius`](https://github.com/RodrigoDMU/programming-for-data-analytics/blob/main/assignments/weatherreadings1.csv).

**Summary:**
- **Data Loading:** Loaded the CSV file into a `pandas` DataFrame.
- **Data Preprocessing:** Converted the `reportStartDateTime` column to a datetime format for proper time-based plotting.
- **Visualization:** Created a scatter plot and a line plot for temperature over time, with appropriate customization (labels, grid, title).

*****

**- Assignment 3: Domains**

**Task description:** Create a notebook called [`assignment03-pie.ipynb`](https://github.com/RodrigoDMU/programming-for-data-analytics/blob/main/assignments/assignment03-pie.ipynb). The note book should have a nice pie chart of peoples email domains in the csv file at the [url](https://drive.google.com/uc?id=1AWPf-pJodJKeHsARQK_RHiNsE8fjPCVK&export=download). This csv file has [`1000 people`](https://github.com/RodrigoDMU/programming-for-data-analytics/blob/main/assignments/people-1000.csv). You may download the data or link to it.

**Summary:**
- **Data Loading:** The dataset was loaded into a `pandas` DataFrame.
- **Email Domain Extraction:** The email domain was extracted from the `Email` column by splitting the string at the `@` symbol.
- **Domain Counting:** The frequency of each domain was calculated using `value_counts()`.
- **Visualization:** A pie chart was created to represent the distribution of email domains, with labels, percentages, and a customized color palette.

*****

**- Assignment 5: Risk**

**Task description:** Write a program called [`assignment_5_risk.ipynb`](https://github.com/RodrigoDMU/programming-for-data-analytics/blob/main/assignments/assignment_5_risk.ipynb). The program should simulates 1000 individual battle rounds in Risk (3 attacker vs 2 defender) and plots the result. One battle round is one shake of the attacker and defender dice. ***For the last few marks:*** A more complicated version simulates a full series of rounds for armies of arbitrary sizes, until one side is wiped out, and plots the results.

**Summary:**
- **Data Simulation:** Simulated individual battle rounds and full battles between the attacker and defender.
- **Battle Logic:** Each battle round was decided by comparing the dice rolls of the attacker and defender, with the number of troops lost based on the outcomes.
- **Visualization:** Two bar charts were created:
    - **For 1000 battle simulations:** This showed the total number of wins for the attacker, the defender, and the number of ties.
    - **For a full battle:** This tracked the number of troops remaining for both the attacker and defender after each round of the battle, providing a clear visual representation of how the battle unfolded.

*****

**- Assignment 6: Knock Airport Weather**

**Task description:** Create a python file or notebook called [`assignment_6_weather.ipynb`](https://github.com/RodrigoDMU/programming-for-data-analytics/blob/main/assignments/assignment_6_weather.ipynb). Get the data from this [link](https://cli.fusio.net/cli/climate_data/webdata/hly4935.csv). 

- Plot the following:
    - The temperature over time.
    - The mean temperature for each day.
    - The mean temperature for each month.

- For the remaining task:
    - Plot the windspeed data (note that there may be missing data in this column).
    - Create a plot of the rolling windspeed (e.g., over a 24-hour period).
    - Plot the maximum windspeed for each day.
    - Calculate and plot the monthly mean of the daily maximum windspeed.

**Summary:**
- **Data Loading and Preprocessing:** The data was successfully loaded from the provided link, and necessary columns were extracted and preprocessed for analysis.
- **Temperature:** The temperature over time was plotted, showing how the temperature varied with time. I also calculated and plotted the daily and monthly mean temperatures to summarize the temperature trends.
- **Windspeed:** The windspeed data was plotted over time, and missing values were handled using forward-fill. Additionally, I visualized the rolling windspeed over a 24-hour period, the maximum windspeed for each day, and the monthly mean of daily maximum windspeeds.
- **Visualizations:** All the required plots were created using matplotlib. The plots for temperature, windspeed, rolling windspeed, and maximum windspeed were all formatted with appropriate labels, titles, legends, and gridlines to make them easy to interpret.

*****

## Final Project

*****

## Author

**Rodrigo De Martino Ucedo:**
 I am currently studying Higher Diploma in Science in Data Analysis at Atlantic Technological University. For more information or questions, please contact me on GitHub or add me on [LinkedIn](https://www.linkedin.com/in/rdmdemartino/).

*******
## End
last commit on 14/12/2024