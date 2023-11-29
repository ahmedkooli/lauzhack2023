# lauzhack2023

Dear participants, 

We are happy to welcome you to the Swisscom Challenge for Lauzhack 2023. This year, we are all about revolutionising customer interactions. Find the description of the challenge bellow together with some information about the data we provide you. Also, if you would like to use AWS resources for your implementation, do not hesitate to contact us or the AWS team :) 

We are happy to answer your questions on site or in our discord space. 

Happy hacking! 

# Challenge Description

Join us in revolutionising customer interactions! Your mission is to engineer a retrieval system that extracts vital information from our company website. This will help us empower our support team to answer customer queries with lightning speed, enhancing the overall user experience. We will provide you with data from the website already scraped and a set of questions and answers so that you can test your model. You are free to use LLM APIs, small NLP models or any trick you can come up with, we are looking for a creative, interactive and user-friendly solution that ensures seamless access to critical data. 

## Data Description 
We provide you with data scraped from Swisscom's public website. The data is contained in the file: ```swisscom_webpage.json```

The structure of the elements in the json file is the following: 

* ```vector_field```: List representing the embedding of the text. Dimension: 1536
* ```text```: paragraph of text extracted from the website.
* ```metadata```:
  -  ```source```: link to the source page.
  -  ```language```: language of the text. Can be German (de), French (fr), Italian (it), English (en) or None
  -  ```title```: title of the article containing the text
  -  ```created_at```: data of creating of the text
  -  ```last_modified```: latest modification on the text
  -  ```start_index```: - 
