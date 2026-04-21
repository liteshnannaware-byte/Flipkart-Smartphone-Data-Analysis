Project Structure
web_scrap_project.ipynb: The main Jupyter Notebook containing the code for scraping, cleaning, and analysis.

clean_flipkart_mobile_data.csv: (Generated) The final cleaned dataset used for analysis.

📊 Methodology
Request & Parse: Sending HTTP requests to Flipkart search pages and parsing the HTML content.

Extraction: Targeting specific HTML tags to retrieve Mobile Name, Price, Rating, Number of Reviews, and Specifications.

Storage: Organizing the raw data into a Pandas DataFrame.

Data Cleaning: - Removing special characters (e.g., ₹, commas) from Price columns.

Converting numeric strings to appropriate data types (int/float).

Handling null values.

EDA: Visualizing trends such as the relationship between price and ratings or the most popular brands.
