# Time_Series_plotly.express
While working on Time-Series Data over my Summer Internship 2023 as Statistical Data Mining Analyst, I found a very simple and useful visualization using Python plotly.express library that can help view time series data with ease. 

![alt text](https://github.com/ekamkhaira98/Time_Series_plotly.express/blob/main/Visualization.png)

Here's the implemenation of Python code for the same on a Mock temporal data.

Step 1- Install plotly

Step 2- Import Pandas for CSV file Data Input, plotly.express and matplotlib for visualization aspect

Step 3- Set parameters for Graph Display

Step 4- Import Time-Series Dataset with atleast one Column with Count Value e.g in this case column: Total-Logins represents Total Logins of a User in an Hour period

Step 5- Extract data of a User or particular object which you want to view e.g I want to view total logins of User1 over a period of 3 Months

Step 6- Two Columns are being utilized by plotly. One column contains Datetime values, other one has Count values

-> Set rangeslider_visible parameter as True to view a Date Range Slider in the viz

-> Set rangeselector parameter as a dictionary of buttons. Here we are adding 3 buttons with month-wise backward step.

-> Customise the values as per your requirements
