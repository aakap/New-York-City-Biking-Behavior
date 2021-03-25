# New-York-City-Biking-Behavior

Regression Analysis Steps
1. Use WEEKDAY function to convert date-time format to day of week by number
2. Use MOD function to shift the day of week number to start the week at Saturday 
3. Use MONTH function to extract month number from date-time format
4. Use IF statement to convert trace precipitation entries to 0.01 inches
5. Run a multivariate regression using ToolPak with total crossings as y and day of week, month, precipitation, high temp, low temp as x variables
6. Use IF statement to determine whether day of week is weekend or not. Use 1 for weekend and 0 for weekday to make binary variable
7. Run a multivariate regression using ToolPak with total crossings as y and weekend status, month, precipitation, high temp, low temp as x variables
8. On a scatterplot, graph total crossings vs high temp and total crossings vs precipitation amount
9. Fit a linear trendline to the graphs and determine line of best fit + R-squared value
10. Analyze results 
