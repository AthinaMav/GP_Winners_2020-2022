# GP_Winners_2020-2022

Simple Java project that asks user for input (Year, Grand Prix) and provides them with the names of the driver and team that won. 
The data comes from a csv file and is stored in an ArrayList of Race objects.
Before the program iterates through the ArrayList, the input is validated with 2 if conditions. One checks if the year provided is among 2020-2022 and the second checks if the particular Grand Prix was held during 2020-2022 seasons

Once the input is validated, the program iterates though the ArrayList and prints the winner driver and team.
There's another if condition here checking if the year and Grand Prix match cause even if the user gives accurate input, it doesn't mean that said Grand Prix took place in that year.

The validity of the user input for the Grand Prix is determined by the names from the official F1 site https://www.formula1.com/en/results/archive-1950-2016.html
