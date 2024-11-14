# Minning_Lab1_Task
Task 1.Create a series with index=['USSR','Germain','China','Japan','USA']) and population values
([8700000,4200000,3000000,2100000,400000]. Find the country where population is
greater than 3 million. After that, convert this series into dictionary form.

Task 2.
You are given a Pandas Series representing monthly sales figures for a product over a year.
monthly_sales = pd.Series([200, 300, None, 150, 400, None, 350, 300, 200, None, 450,
500])
However, some months have missing data. Replace any missing values with the average
sales for the year, then reindex the Series to add two more months to the end, setting their
values to NaN. Finally, fill these new NaN values with 0. What methods would you use to
handle missing values, calculate the average, and reindex the Series?

Task 3.
sensor_data = pd.DataFrame({ 'Sensor_1': [25, 145, np.nan, 152, 130, np.nan, 40, 60, 180,
90], 'Sensor_2': [np.nan, 60, 75, 140, np.nan, 160, 155, 80, 110, 145], 'Sensor_3': [100,
np.nan, 135, 165, 45, 150, np.nan, 155, 120, 170], 'Sensor_4': [120, 135, 140, np.nan, 125,
180, np.nan, 70, 160, 150], 'Sensor_5': [140, np.nan, 155, 60, 175, 130, 95, np.nan, 150,
115] })

A sensor network monitors temperature and humidity, but due to technical issues, some
data points are either missing or unusually high, exceeding the normal threshold of 150.
Given a dataset with sensors as rows and hourly readings as columns, the company wants
all NaN values and values above the normal threshold to be adjusted. How would you
approach detecting and rectifying these anomalies?
(Students think ! How you shall adjust the NaN and values above the threshold ?)

Task 4.
A researcher has a 1-dimensional array representing monthly rainfall in millimeters over
the past two years.
rainfall_data = np.array([ 45, 120, 250, 85, 60, 30, 110, 55, 40, 180, 210, 65, 95, 140, 35,
60, 220, 125, 80, 70, 90, 200, 50, 160 ])
They want to extract only the months where the rainfall was above 50mm and below
200mm. Given an array of rainfall values, use array slicing and conditional selection to
isolate the data within this range. What would you use to achieve this in NumPy?

Task 5.
A researcher has data representing the pixel values of a small 5x5 grayscale image captured
by a satellite.
pixel_values = np.array([23, 45, 167, 89, 34, 120, 56, 200, 78, 144, 34, 255, 189, 67, 90,
160, 128, 45, 210, 75, 44, 88, 77, 150, 99])
Each pixel value is an integer from 0 to 255, indicating the intensity of light. The data was
initially captured as a 1-dimensional array and needs to be reshaped to form the 5x5 grid.
Similarly, all pixel values above 150 needs to be set to 150. At the end, slice and extract
the central 3x3 region of the image matrix.
