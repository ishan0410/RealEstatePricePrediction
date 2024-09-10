# Real Estate Price Prediction

1.	Data Loading and Exploration:
	•	The notebook begins by importing essential libraries such as Pandas, NumPy, and Matplotlib for data manipulation and visualization.
	•	The Bangalore home prices dataset is loaded into a DataFrame (df1), and initial exploration checks the dataset’s shape, columns, and unique values in the area_type column.
2.	Data Preprocessing:
	•	Feature Selection: Columns such as area_type, society, balcony, and availability are dropped, reducing the DataFrame (df2).
	•	Handling Missing Values: Missing values are identified, and rows containing NA values are dropped, resulting in a cleaned DataFrame (df3).
3.	Feature Engineering:
	•	A new feature, bhk (Bedrooms Hall Kitchen), is created by extracting the number of bedrooms from the size column.
4.	Further Exploration:
	•	The total_sqft feature is further explored to understand its characteristics.
