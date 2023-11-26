# Twitter Analysis Project

## Introduction
Welcome to the Twitter Analysis Project! This endeavor delves into the expansive and dynamic world of Twitter data, exploring tweets to uncover patterns and insights. The project stands out by employing PySpark, a powerful tool for big data processing, enabling efficient analysis through Resilient Distributed Datasets (RDDs), MapReduce operations, and DataFrame transformations.

Utilizing a dataset composed of JSON strings, we focus primarily on tweets. Our approach leverages the scalability and speed of PySpark to process large volumes of data, applying RDD transformations, MapReduce methods for distributed computing, and DataFrame operations for structured data analysis.

This project is an excellent showcase of big data processing capabilities, offering insights into the nuances of social media interactions and trends on Twitter.

![pyspark](https://www.mytechmint.com/wp-content/uploads/2021/03/PySpark-Tutorial-myTechMint.jpeg)
![twitter](https://laverdadnoticias.com/export/sites/laverdad/img/2023/08/31/twitter_cambio_su_logo_por_la_x.jpg_939674776.jpg)
## Data Overview
The analysis utilizes two primary data sources:

- `twitter.txt`: Contains the tweet data, represented as rows of JSON strings.
- `users-partition.pickle`: A pickle file with a partition over 452,743 Twitter users, categorized into 7 groups.

The analysis revolves around tweet data, which includes numerous fields as per the Twitter API documentation. Key fields we focus on include:
- `created_at`: The timestamp of the tweet.
- `id_str`: Unique identifier for the tweet.
- `text`: The content of the tweet.
- `user`: Details about the author of the tweet, including user ID, name, and screen name.
- `retweeted_status`: Information about retweeted tweets.
- `entities`: Contains hashtags and URLs mentioned in the tweet.
Additionally, we explore a partition of 452,743 Twitter users, divided into 7 groups.

## Installation and Setup
To get started with this project, clone the repository and ensure you have Jupyter Notebook installed. The analysis requires specific Python libraries, which can be installed using the provided `requirements.txt` file.

```bash
git clone https://github.com/abdoufermat5/twitter-analysis.git
cd twitter-analysis/
pip install -r requirements.txt
```

## Usage
To run the analysis:
1. Open the Jupyter Notebook in your environment.
2. Execute the cells in sequence to process the data and view the results.
3. Explore the tweet data.

## Results and Discussion
The notebook presents various insights into Twitter usage patterns, popular hashtags, user behavior, and more. Key findings include:

[TODO]
