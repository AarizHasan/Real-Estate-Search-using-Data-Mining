**Title: Real Estate Search using Data Mining in Bengaluru**

**Description:**

This project delves into the world of real estate data mining, focusing on cleaning and pre-processing property data from Bengaluru, India. The data is sourced from a CSV file named "bengaluru_house_prices.csv".

**Key Steps:**

1. **Data Loading and Cleaning:**
   - Leverages the pandas library to load the CSV data.
   - Implements data cleaning techniques:
     - Removes irrelevant features like "area_type", "society", "balcony", and "availability".
     - Handles missing values by identifying and dropping rows with missing data.
     - Creates new features:
       - "bhk" (number of bedrooms) extracted from the "size" feature.
       - "price_per_sqft" calculated to understand per-square-foot pricing.

2. **Exploratory Data Analysis (EDA):**
   - Analyzes the distribution of crucial features like "price_per_sqft" and location.
   - Identifies and removes outliers:
     - Eliminates data points that deviate significantly from the expected price per square foot for their location.
     - Addresses outliers based on BHK category (number of bedrooms).

3. **Data Pre-processing:**
   - Prepares the data for further analysis, such as building machine learning models, by removing outliers.

4. **Data Visualization:**
   - Employs scatter charts to visualize the relationship between property size, price, and number of bedrooms.

**Libraries Used:**

- pandas
- numpy
- matplotlib
