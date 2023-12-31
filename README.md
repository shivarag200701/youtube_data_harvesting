# Youtube-Data-Scrapping
## Content

[Introduction](#Introduction)

[Features](#Features)

[Technologies_Used](#Technologies Used)

[Process_Flow](#Process Flow) 

[Application_Flow](#Application Flow)

[Additional_Information](#Additional Information)

[License](#License)

[Conclusion](#Conclusion)

## Introduction
This project is a YouTube API scrapper that allows users to retrieve and analyze data from YouTube channels. It utilizes the YouTube Data API to fetch information such as channel statistics, video details, comments, etc. This project also allows the user to store data in MongoDB and also allows the user to migrate the data to an SQL database. The Scrapper provides various functionalities to extract and process YouTube data for further analysis and insights.

## Features
The YouTube Data Scraper offers a range of features to help you extract and analyze data from YouTube. Some of the key features include:

**`Retrieve channel data:`** 
Get detailed information about YouTube channels, including subscriber count, view count, video count, and other relevant metrics, and also extract data such as video title, description, duration, view count, like count, dislike count, and publish date for individual videos.

**`Store Data In MongoDB Atlas:`** 
Store the collected YouTube data in MongoDB Atlas for easy retrieval and future reference.

**`Retrieve Data From MongoDB Atlas:`** 
Retrieve the stored data from the MongoDB server to verify whether.

**`Create tables In SQL`** 
To create tables in MySql server

**`Migrate channel information from MongoDB Atlas to SQL:`** 
Migrate basic channel information from the MongoDB Atlas server to the SOL server

**`Migrate video information from MongoDB Atlas to SQL`** 
Migrate video information from the MongoDB Atlas server to the SOL server for individual videos.

**`Migrate comment information from MongoDB Atlas to SQL`** 
Migrate comment information from the MongoDB Atlas server to the SOL server for individual videos.

**`channel analysis`** 
Perform a list of SQL queries on the generated SQL tables.


## Technologies Used
**`Python:`** The project is implemented using Python programming language.

**`YouTube Data API:`** Utilizes the official YouTube Data API to interact with YouTube's platform and retrieve data.

**`Streamlit:`** The user interface and visualization are created using the Streamlit framework, providing a seamless and interactive experience.

**`MongoDB:`** The collected data can be stored in a MongoDB database for efficient data management and querying.

**`MySQL:`** A powerful open-source relational database management system used to store and manage the retrieved data.

**`PyMongo:`** A Python library that enables interaction with MongoDB, a NoSQL database. It is used for storing and retrieving data from MongoDB in the YouTube Data Scraper.

**`mysql.connector:`** A MySQL adapter for Python that allows seamless integration between Python and MySQL. It enables the YouTube Data Scraper to connect to and interact with the MySQL database.

**`googleapiclient:`** The Google API Client Library for Python is designed for Python client-application developers. It offers simple, flexible access to many Google APIs.

**`Pandas:`** A powerful data manipulation and analysis library in Python. Pandas is used in the YouTube Data Scraper to handle and process data obtained from YouTube, providing functionalities such as data filtering, transformation, and aggregation.

**`pip install -r requirements.txt:`** To install the required dependencies.

## Process Flow
### Obtain YouTube API credentials:
> Visit the `Google Cloud Console`.

> Create a new project or select an existing project.

> Enable the `YouTube Data API v3` for your project.

> Create `API credentials` for youtube API v3.

### ETL Process
> `Extracting` Data from youtube API.

> `Transforming` data into required format.

> `Loading` Data into SQL

## Application Flow
Input the Channel Id and click on `Retrieve Channel Data` in order to retrive data from Youtube API.

Select `Retrieve Channel Data` button from Retrieve Channel Data menu at the tabs section.

Click on `Store Data In MongoDB Atlas` to store data in MongoDB Lake.

Click on `Retrieve Data From MongoDB Atlas` to check whether the data is stored properly in MongoDB.

Create tables in SQL using `Create tables In SQL`.

Click on `Migrate channel information from MongoDB Atlas to SQL` to migrate channel information from MongoDB Lake to MySQL.

Click on `Migrate video information from MongoDB Atlas to SQL` to migrate video information from MongoDB lake to MySQL.

Click on `Migrate comment information from MongoDB Atlas to SQL` to migrate comment information from MongoDB lake to MySQL.

`channel analysis` tab allows the user to select a set of 10 queries to run over the generated SQL tables







## Additional Information
Please note that when using this application, it is essential to comply with the YouTube Data API's terms of service and adhere to its usage limits to ensure uninterrupted access to the API. If you encounter any issues or have questions regarding the YouTube Data Scraper, please refer to the project's detailed documentation available in the GitHub repository.

## License
The YouTube Data Scraper is released under the MIT License. Feel free to modify and use the code according to the terms of the license.

## Conclusion
This YouTube API scrapper project aims to provide a powerful tool for retrieving, analyzing, visualizing YouTube data, and storing data in Data Lake and SQL SERVER,  enabling users to gain valuable insights into channel performance, video engagement, and audience feedback.
