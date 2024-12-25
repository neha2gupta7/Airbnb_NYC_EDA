# Airbnb NYC 2019 EDA - Exploratory Data Analysis

**Project Overview**

This project focuses on conducting an Exploratory Data Analysis (EDA) of the Airbnb NYC 2019 dataset. The primary goal is to extract valuable insights about Airbnb listings in New York City by analyzing key factors that affect pricing, availability, and overall performance. The analysis aims to assist Airbnb hosts in optimizing their listings and provide data-driven insights for improving customer experiences.

**Dataset**

The dataset used in this project is the Airbnb NYC 2019 dataset, which contains around 49,000 observations and 16 columns. The dataset includes information on:
-	Listing IDs, host IDs
-	Neighborhood and geographical coordinates
-	Room types and prices
-	Minimum nights, number of reviews
-	Availability and review information

**Columns in the dataset:**

-	id: Listing ID
-	name: Name of the listing (text)
-	host_id: Host ID
-	host_name: Name of the host
-	neighbourhood_group: NYC borough (categorical)
-	neighbourhood: NYC neighborhood (categorical)
-	latitude: Latitude of the listing (numeric)
-	longitude: Longitude of the listing (numeric)
-	room_type: Type of room (categorical)
-	price: Price per night (numeric)
-	minimum_nights: Minimum number of nights (numeric)
-	number_of_reviews: Total number of reviews (numeric)
-	last_review: Date of the last review (datetime)
-	reviews_per_month: Average number of reviews per month (numeric)
-	calculated_host_listings_count: Number of listings by the host (numeric)
-	availability_365: Number of available days in a year (numeric)

**Objectives**

1.	Perform data exploration and cleaning.
2.	Analyze key factors that impact pricing and availability.
3.	Understand neighborhood and room type trends.
4.	Identify correlations between price, number of reviews, and availability.
5.	Provide actionable insights for Airbnb hosts and travelers.

**Project Workflow**

**1. Data Exploration and Cleaning**

-	Explore the dataset to get an initial understanding of the data distribution.
-	Handle missing values:
    * Columns with missing values: last_review, reviews_per_month, name, host_name.
    * Impute or drop missing values based on the data’s nature and analysis needs.
- Convert data types for easier analysis, e.g., convert last_review to datetime format.

**2. Data Visualization**

-	Use visualizations to uncover trends and relationships:
    * Neighborhood distribution: Listings across NYC boroughs.
    * Price distribution: Understand price ranges by room type and borough.
    *	Availability: Analyze how availability changes across neighborhoods.
    * Correlations: Investigate how price relates to other factors (e.g., number of reviews, room type).

Tools used: matplotlib for plotting visualizations with high contrast for better clarity.

**3. Key Findings**

-	Price vs. Neighborhood: Listings in Manhattan are priced higher on average compared to other boroughs.
-	Room Type Trends: Entire homes/apartments tend to be more expensive, while shared rooms are more affordable.
-	Reviews and Listings: Hosts with more listings tend to have fewer reviews per property, indicating a possible impact on customer engagement.
-	Minimum Nights and Occupancy: Shorter minimum night requirements are linked to higher booking rates.
  
**4. Actionable Insights**

-	Airbnb hosts can optimize pricing by considering neighborhood and room type trends.
-	Hosts should aim for shorter minimum stays to improve occupancy.
-	Increasing engagement and maintaining listing quality helps attract more reviews and bookings.

**Technologies Used**

-	Python for data analysis
-	Pandas for data manipulation
-	Matplotlib for visualizations
-	Jupyter Notebook for interactive analysis

**How to Run This Project**

**Prerequisites**

Ensure you have Python installed along with the following libraries:
  -  pandas
  -  matplotlib
  -  seaborn (optional for advanced visuals)

**Steps to Run the Analysis**

1. Clone the repository:
   **git clone https://github.com/neha2gupta7/Airbnb_NYC_EDA/tree/main**

2. Navigate to the project directory:
   **cd airbnb-nyc-2019-eda**

3. Install the required libraries:
   **pip install -r requirements.txt**

4. Open the Jupyter notebook:
   **jupyter notebook Airbnb_NYC_EDA(Neha Gupta).ipynb**

5. Run the notebook to view the analysis and visualizations.

**Project Structure**

* Airbnb_NYC_EDA(Neha Gupta).ipynb: The main notebook containing the analysis and visualizations.
* data/: Directory containing the Airbnb NYC 2019 dataset (AB_NYC_2019.csv).
* plots/: Directory for storing visualizations generated during analysis.




   


















