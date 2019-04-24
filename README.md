# Real Estate
## Link for the project: https://knishina.github.io/clean_real_estate/

### Purpose.
- Because Tech is exciting, but unpredictable.
- A back-up income strategy is needed.
- For Happy / Early Retirement

### A Case Study.
- Buy single family house in expanding job market in South Carolina
- Be lazy for 10 years and collect rent
- Check back to see value increase 4x times after 10 years
- Factors considered for property investment:
 >> * Cost of single family house
 >> * School ratings
 >> * Job growth
 >> * Crime rate
 >> * Cost-to-Rent ratio

### Data Sources.
There are a number of different data sources that were utilized.
- [Zipcode CSV](https://tools.usps.com/go/ZipLookupAction_input) file from USPS 	
- [Rental Data](http://www.city-data.com/) from City Data API 
- [Rental & Cost of Single Family House](https://www.zillow.com/howto/api/APIOverview.htm) from Zillow
- [Property Data](https://www.quandl.com/tools/api) from Quandl API
- [Great Schools API](https://www.greatschools.org/)
- [Crime Rate Data](http://www.crimerate.com/) retrieved from Crime Rate website
- [Job Growth Data](https://www.bls.gov/sae/#tables) retrieved from Bureau of Labor Statistics	

### Retrieval Methods.
Once the data sources were identified, the data gathered and munged.
- APIs to retrieve data using requests module
- Web scraping using BeautifulSoup module
- Converting XML data to python dictionaries using XmlDict module
- Converting HTML tags into text and selecting data using split function
- Converting unstructured scraped data using regular expressions
- Python Pandas for aggregation and clean up of data

### Data Summary & Metrics.
- Data retrieved for 407 zip codes in South Carolina state.
- After cleanup and aggregation, final data set contains data for 206 zip codes.
- Normalization of 'Rent', 'School Ratings', 'Job Growth' & 'Crime Rate' to a factor of '1'.
- Summary metric derived by adding the normalized values.


