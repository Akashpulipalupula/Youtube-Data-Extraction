YouTube Data Harvesting and Warehousing using SQL, MongoDB, and Streamlit

This project focuses on extracting data from YouTube and storing it in different databases.

To execute the project, you'll need the following applications:

YouTube API: For extracting the data from YouTube.
MongoDB: To store the data in a NoSQL format.
MySQL: To store the data in a tabular form.
Streamlit: For creating the web application.
Programming Language: Python

The application consists of four tabs:

Home: The Home page provides a brief explanation of the project and the workflow involved.
Extract Data: The Extract Data page allows users to enter a YouTube Channel ID and extract the data.
Display: The Display page shows the extracted data stored in MongoDB.
SQL Queries: The SQL Queries page displays the results/analysis for a set of predefined questions based on the data stored in MySQL.
Workflow:

On the Extract Data page, enter the Channel ID of the YouTube channel from which you want to extract data, then click on the Extract button.
The data will be extracted and stored as a separate document in MongoDB. Simultaneously, the data will also be stored in the MySQL database in the required tables.
Repeat the above steps for any number of Channel IDs.
After extracting and storing the data, move to the SQL Queries page to view the analysis and results for the predefined questions.
To view the data stored in the MongoDB database, navigate to the Display tab.
