# ECommerceProductExtractor
Import necessary libraries:

bs4 (Beautiful Soup): For parsing HTML content.
requests: For making HTTP requests to fetch web pages.
pandas: For creating and manipulating DataFrames.
numpy: For numerical operations (not used directly in this code).
Define the extract_product_info function:

Takes a product URL as input.
Sends an HTTP GET request to the URL.
Parses the HTML content using Beautiful Soup.
Finds the desired product information (title, price, rating, reviews) using appropriate CSS selectors.
Creates a dictionary with the extracted information and returns it.
Define the scrape_multiple_products function:

Takes a list of product URLs as input.
Iterates over each URL.
Calls the extract_product_info function for each URL.
Appends the extracted product information to a list.
Returns the list of product information.
Create a list of product URLs:

Add the URLs of the products you want to scrape.
Scrape product information:

Call the scrape_multiple_products function with the list of URLs.
Store the scraped product information in a variable.
Create a pandas DataFrame:

Create a pandas DataFrame from the scraped product information.
Display the DataFrame:

Print the DataFrame to the console
