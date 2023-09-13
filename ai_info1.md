**Project: Weather Data Analysis using Numpy**

**Introduction:**  
Numpy is a foundational package for numerical computations in Python. It provides support for large multi-dimensional arrays and matrices, along with an assortment of high-level mathematical functions to operate on these arrays. 

In this project, you'll analyze a dataset of weather information to draw some insights. This will allow you to practice the fundamentals of Numpy in a real-world scenario.

**Dataset:**  
Imagine you've been given a month's worth of weather data for a city. This data contains the daily maximum temperature (in Fahrenheit), daily minimum temperature, and the amount of rainfall (in inches).

Here's the sample dataset for a month (30 days):

```python
max_temperatures = np.array([75, 78, 82, 74, 69, 68, 70, 72, 74, 77, 80, 79, 78, 76, 75, 73, 71, 70, 68, 68, 70, 73, 74, 76, 77, 80, 81, 82, 83, 84])
min_temperatures = np.array([62, 65, 68, 60, 57, 56, 58, 59, 60, 63, 65, 64, 63, 62, 61, 60, 59, 57, 55, 54, 56, 59, 60, 62, 63, 66, 68, 69, 70, 71])
rainfall = np.array([0.05, 0, 0, 0.1, 0.25, 0.5, 0.05, 0, 0, 0, 0, 0.1, 0.15, 0.2, 0.05, 0, 0, 0.3, 0.4, 0.2, 0, 0, 0, 0, 0, 0.1, 0, 0, 0, 0])
```

**Tasks:**  

1. **Basic Statistics:**  
    a. Find the average maximum, minimum temperature and average rainfall for the month.  
    b. Find the highest and lowest temperatures for the month.  
    c. Identify the day(s) when the highest and lowest temperatures occurred.  
    d. Calculate the variance and standard deviation of the max and min temperatures.

2. **Data Manipulation:**  
    a. Convert the temperature data from Fahrenheit to Celsius. (Formula: \( (°F - 32) × 5/9 = °C \))  
    b. Find the days where the temperature was above 75°F and below 60°F.  
    c. Calculate the total rainfall for the month.  
    d. Find out the days when there was no rainfall.

3. **Comparison:**  
    a. How many days had a temperature difference (between max and min) of more than 15°F?  
    b. Compare the rainfall data with the temperature, and see if there’s any correlation between the amount of rainfall and the temperature drop (difference between max and min temperatures).

4. **Visualization (Optional):**  
    This is primarily a Numpy project, but for a more visual understanding, you can plot the data. Use `matplotlib` or any other plotting library to plot:  
    a. A line chart for max and min temperatures.  
    b. A bar chart for rainfall.

**Tips and Tricks:**  
- Use Numpy's in-built functions to perform operations like mean, max, min, variance, and standard deviation.
- Logical indexing can be very helpful to filter data in arrays.

**Expected Outcome:**  
By the end of this project, you would have practiced various Numpy operations and gotten an understanding of how to manipulate and analyze data. Moreover, you'll have an appreciation for how Python and Numpy can provide insights into real-world data.