# Twitter-Scraping
![image](https://github.com/balajeeycp2k/Twitter-Scraping-/assets/112715562/834eb709-d472-40cd-998c-6ca61c3fe2ac)


Twitter Scraper using Streamlit and MongoDB
This code demonstrates how to scrape Twitter data using the Streamlit framework and store it in a MongoDB database. It provides a user interface where the user can specify the keyword, start date, end date, and limit for the Twitter search. The scraped data is then displayed on the main page and can be uploaded to MongoDB or downloaded in CSV or JSON format.

Using snscrape library for Twitter scraping
The code utilizes the snscrape library, specifically the TwitterSearchScraper module, for scraping Twitter data. It searches for tweets containing the specified keyword within the given date range. The limit parameter determines the maximum number of tweets to be scraped.

MongoDB integration
The code connects to a MongoDB database using the PyMongo library. The scraped tweets are stored in a collection named after the keyword. The insert_many method is used to insert the tweets as documents in the collection.

Streamlit user interface
The code sets up a user interface using Streamlit. The sidebar allows the user to input the keyword, start date, end date, and limit for the Twitter search. The main page displays the scraped tweets in a table format. The user can choose to upload the data to MongoDB or download it in CSV or JSON format.

Uploading and downloading data
The code provides functionality to upload the scraped data to MongoDB or download it in CSV or JSON format. When the user clicks the "upload to MongoDB" button, the data is inserted into the corresponding collection in the database. The "Download" button allows the user to choose the file format (CSV or JSON) and download the data accordingly. Success messages are displayed when the upload or download is completed.

Overall, this code demonstrates a simple Twitter scraper with user interaction through Streamlit and data storage in MongoDB. It provides flexibility in specifying the search parameters and offers options for data manipulation and export.
