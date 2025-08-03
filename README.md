# Fetching-Processing-Analyzing-Data-from-public-APIs-using-Python

This project demonstrates the use of simple APIs in Python, including RandomUser, Fruityvice, and Official Joke API. It showcases how to interact with APIs, retrieve data, and process it into structured formats using Python libraries like `randomuser`, `requests`, and `pandas`.

## Project Overview

It guides users through fetching, processing, and analyzing data from three distinct APIs: **RandomUser**, **Fruityvice**, and **Official Joke API**. The notebook serves as a practical introduction to API usage, data retrieval, and manipulation using Python libraries such as `randomuser`, `requests`, and `pandas`.

The primary goals are to:

- Learn to integrate and use Public APIs for data retrieval.
- Demonstrate data processing into structured formats (e.g., pandas DataFrames).

## Achievements

The project successfully accomplishes the following:

### 1. RandomUser API

- Generated random user data (e.g., names, emails, profile pictures) for 10 users using the `randomuser` library.
- Created a pandas DataFrame containing user details such as name, gender, city, state, email, date of birth, and picture URLs.
- Completed an exercise to extract profile picture URLs for 10 users.
- **Sample Output**: A DataFrame with user details and a list of profile picture URLs.

### 2. Fruityvice API

- Retrieved nutritional and taxonomic data for various fruits using the `requests` library.
- Converted JSON data into a pandas DataFrame with columns like name, family, genus, and nutritional values (calories, fat, sugar, carbohydrates, protein).
- Successfully queried specific fruit details, such as the family and genus of cherries (`Rosaceae`, `Prunus`) and the calorie content of a banana (96 calories).
- **Sample Output**: A comprehensive DataFrame of fruit data and specific query results.

### 3. Official Joke API

- Fetched 10 random jokes using the `requests` library.
- Processed the JSON response into a pandas DataFrame, retaining only the `setup` and `punchline` columns after dropping `type` and `id`.
- **Sample Output**: A clean DataFrame displaying 10 jokes with their setups and punchlines.

### 4. Educational Outcomes

- Demonstrated how to use Python libraries (`randomuser`, `requests`, `pandas`, `json`) to interact with APIs.
- Showcased data normalization techniques (e.g., `pd.json_normalize` for nested JSON).
- Provided practical exercises to reinforce API interaction and data manipulation skills.
- Highlighted the advantages (automation, efficiency) and disadvantages (security concerns) of using APIs.

## Types of APIs Used

The project utilizes three public, no-authentication-required APIs, each serving a different purpose:

### 1. RandomUser API

- **Type**: RESTful API
- **Purpose**: Generates random user data for testing and development purposes, similar to Lorem Ipsum for text but for user profiles.
- **Data Provided**: User details like name, gender, email, address, date of birth, profile pictures, etc.
- **Access Method**: Used via the `randomuser` Python library, which simplifies interaction with the API's endpoints (e.g., `get_full_name()`, `get_email()`, `get_picture()`).

### 2. Fruityvice API

- **Type**: RESTful API
- **Purpose**: Provides detailed information about fruits, including nutritional content and taxonomic classification.
- **Data Provided**: Fruit name, ID, family, order, genus, and nutritional data (calories, fat, sugar, carbohydrates, protein).
- **Access Method**: Accessed using the `requests` library to fetch JSON data from the endpoint `https://fruityvice.com/api/fruit/all`.

### 3. Official Joke API

- **Type**: RESTful API
- **Purpose**: Delivers random jokes from a public database for entertainment or testing purposes.
- **Data Provided**: Jokes with fields like `id`, `type`, `setup`, and `punchline`.
- **Access Method**: Accessed using the `requests` library to retrieve data from the endpoint `https://official-joke-api.appspot.com/jokes/ten`.

## Summary

This project successfully demonstrates the practical use of APIs in Python for fetching and processing diverse datasets. It achieves hands-on learning through real-world examples, producing structured data outputs (pandas DataFrames) and answering specific queries. The APIs used are all public, open, and no-authentication-needed RESTful APIs, making them ideal for educational purposes. The notebook provides a solid foundation for understanding API integration, data manipulation, and basic analysis.
