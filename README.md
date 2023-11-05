# YouTubeDataHarvesting
YouTube Data Harvesting and Warehousing using SQL, MongoDB and Streamlit
These import statements suggest that the code may involve working with Google APIs, MongoDB, PostgreSQL, regular expressions, Streamlit for creating a web application or dashboard, and data manipulation with JSON and pandas. The code itself likely contains further functionality related to these libraries and modules.

A function is created to connect the API platform to fetch YouTube data as we require.
Channel ID is given as input in the function and the details required are fetched correspondingly.

YouTube-Data-Harvesting-and-Warehousing-using-SQL-MongoDB-and-Streamlit-Project
To create a Streamlit application that allows users to access and analyze data from multiple YouTube channels.
Skills Takeaway From This Project:
- **Python Scripting:** Python is used for scripting and automation.
- **Data Collection:** Explaining your methods and tools used for data collection.
- **MongoDB:** Database used for storing and managing collected data.
- **Streamlit:** Utilized for data visualization and building interactive dashboards.
- **API Integration:** How APIs are used for data retrieval and integration.
- **Data Management:** Utilizing MongoDB Atlas for NoSQL database and SQL databases for data storage and management.

##Problem Statement:-
The problem is to create a Streamlit application that allows users to access and analyze data from multiple YouTube channels. The application should have the following features:-
1.]Ability to input a YouTube channel ID and retrieve relevant data, including channel name, subscribers, total video count, playlist ID, video ID, likes, dislikes, and comments of each video, using the YouTube API.
2.]Option to store the retrieved data in a MongoDB database as a data lake.
3.]Ability to collect data for up to 10 different YouTube channels and store them in the data lake by clicking a button.
4.]Option to select a channel name and migrate its data from the data lake to a SQL database as tables.
5.]Ability to search and retrieve data from the SQL database using different search options, including joining tables to get channel details.
Approach:-
Set up a Streamlit app: Use Streamlit to build a user-friendly interface where users can interact with the application.
Connect to the YouTube API: Utilize the Google API client library for Python to make requests to the YouTube API and retrieve channel and video data.
Store data in a MongoDB data lake: After retrieving data from the YouTube API, store it in a MongoDB database. MongoDB is suitable for handling unstructured and semi-structured data.
Migrate data to a SQL data warehouse: Once data is collected for multiple channels, migrate it to a SQL database (e.g., MySQL or PostgreSQL) as tables for better organization and querying.
Query the SQL data warehouse: Use SQL queries, possibly with the help of a Python SQL library like SQLAlchemy, to join tables and retrieve specific data based on user input.
Display data in the Streamlit app: Present the retrieved data in the Streamlit app using Streamlit's data visualization features, such as charts and graphs, to facilitate data analysis.
