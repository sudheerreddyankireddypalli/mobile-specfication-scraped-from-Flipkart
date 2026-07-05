# mobile-specfication-scraped-from-Flipkart
The goal of this project is to extract detailed product data of the iPhone 16 from Flipkart using web scraping techniques, clean and organize the data using Python, and analyze it through visualizations to derive valuable business insights
 Data Visualization (EDA)¶
We used matplotlib and seaborn for creating plots to better understand and analyze the data.
Data Collection (Web Scraping)
We used Python libraries like requests and BeautifulSoup to scrape product details of iPhone 16 models from multiple pages on Flipkart.








Key Tasks TO Perfome:
Sent HTTP GET requests to Flipkart search result pages.
Parsed the HTML response to extract:
Product Name
ROM / Storage
Display Type
Camera Specs
Processor Details
Warranty Info
Ratings
Number of Reviews
Price












Univariate Analysis:
Distribution of product ratings
Most common ROM variants
Frequency of different price points
Bivariate Analysis:
Relationship between ratings and number of reviews
Price vs rating comparison
Multivariate Analysis:
Combined analysis of rating, price, and storage
Heatmaps to explore correlations
. Data Cleaning (Using Pandas & Regex)
We used the pandas library to structure the data into a DataFrame and applied regular expressions for text cleaning.

Cleaning Steps:
Removed unwanted characters and spaces.
Extracted rating, review count, and price using regex.
Replaced missing or invalid entries with NaN for consistency.
Converted data types (e.g., strings to floats/integers where required).

